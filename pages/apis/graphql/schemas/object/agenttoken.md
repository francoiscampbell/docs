<!--
  _____   ____    _   _  ____ _______   ______ _____ _____ _______ 
  |  __  / __   |  | |/ __ __   __| |  ____|  __ _   _|__   __|
  | |  | | |  | | |  | | |  | | | |    | |__  | |  | || |    | |   
  | |  | | |  | | | . ` | |  | | | |    |  __| | |  | || |    | |   
  | |__| | |__| | | |  | |__| | | |    | |____| |__| || |_   | |   
  |_____/ ____/  |_| _|____/  |_|    |______|_____/_____|  |_|   
  This file is auto-generated by script/generate_graphql_api_content.sh,
  please build the schema.json by running `rails api:graph:export`
  with https://github.com/buildkite/buildkite/,
  replace the content in data/graphql_data_schema.json
  and run the generation script `./scripts/generate-graphql-api-content.sh`.
-->
<!-- vale off -->
<h1 class="has-pills" data-algolia-exclude>
  AgentToken
  <span class="pill pill--object pill--normal-case pill--large"><code>OBJECT</code></span>
</h1>
<!-- vale on -->


<p>A token used to connect an agent to Buildkite</p>


{:notoc}

<table class="responsive-table responsive-table--single-column-rows">
  <thead>
    <th>
      <h2 data-algolia-exclude>Fields</h2>
    </th>
  </thead>
  <tbody>
    <tr><td><h3 class="is-small has-pills"><code>createdAt</code><a href="/docs/apis/graphql/schemas/scalar/datetime" class="pill pill--scalar pill--normal-case pill--medium" title="Go to SCALAR DateTime"><code>DateTime</code></a></h3><p>The time this agent token was created</p></td></tr><tr><td><h3 class="is-small has-pills"><code>createdBy</code><a href="/docs/apis/graphql/schemas/object/user" class="pill pill--object pill--normal-case pill--medium" title="Go to OBJECT User"><code>User</code></a></h3><p>The user that created this agent token</p></td></tr><tr><td><h3 class="is-small has-pills"><code>description</code><a href="/docs/apis/graphql/schemas/scalar/string" class="pill pill--scalar pill--normal-case pill--medium" title="Go to SCALAR String"><code>String</code></a></h3><p>A description about what this agent token is used for</p></td></tr><tr><td><h3 class="is-small has-pills"><code>id</code><a href="/docs/apis/graphql/schemas/scalar/id" class="pill pill--scalar pill--normal-case pill--medium" title="Go to SCALAR ID"><code>ID</code></a></h3></td></tr><tr><td><h3 class="is-small has-pills"><code>organization</code><a href="/docs/apis/graphql/schemas/object/organization" class="pill pill--object pill--normal-case pill--medium" title="Go to OBJECT Organization"><code>Organization</code></a></h3></td></tr><tr><td><h3 class="is-small has-pills"><code>permissions</code><a href="/docs/apis/graphql/schemas/object/agenttokenpermissions" class="pill pill--object pill--normal-case pill--medium" title="Go to OBJECT AgentTokenPermissions"><code>AgentTokenPermissions</code></a></h3></td></tr><tr><td><h3 class="is-small has-pills"><code>public</code><a href="/docs/apis/graphql/schemas/scalar/boolean" class="pill pill--scalar pill--normal-case pill--medium" title="Go to SCALAR Boolean"><code>Boolean</code></a></h3><p>Whether agents registered with this token will be visible to everyone, including people outside this organization</p></td></tr><tr><td><h3 class="is-small has-pills"><code>revokedAt</code><a href="/docs/apis/graphql/schemas/scalar/datetime" class="pill pill--scalar pill--normal-case pill--medium" title="Go to SCALAR DateTime"><code>DateTime</code></a></h3><p>The time this agent token was revoked</p></td></tr><tr><td><h3 class="is-small has-pills"><code>revokedBy</code><a href="/docs/apis/graphql/schemas/object/user" class="pill pill--object pill--normal-case pill--medium" title="Go to OBJECT User"><code>User</code></a></h3><p>The user that revoked this agent token</p></td></tr><tr><td><h3 class="is-small has-pills"><code>revokedReason</code><a href="/docs/apis/graphql/schemas/scalar/string" class="pill pill--scalar pill--normal-case pill--medium" title="Go to SCALAR String"><code>String</code></a></h3><p>The reason as defined by the user why this token was revoked</p></td></tr><tr><td><h3 class="is-small has-pills"><code>token</code><a href="/docs/apis/graphql/schemas/scalar/string" class="pill pill--scalar pill--normal-case pill--medium" title="Go to SCALAR String"><code>String</code></a></h3><p>The name of the agent</p></td></tr><tr><td><h3 class="is-small has-pills"><code>uuid</code><a href="/docs/apis/graphql/schemas/scalar/id" class="pill pill--scalar pill--normal-case pill--medium" title="Go to SCALAR ID"><code>ID</code></a></h3><p>The public UUID for the agent</p></td></tr>
  </tbody>
</table>




<h2 data-algolia-exclude>Interfaces</h2>
<a href="/docs/apis/graphql/schemas/interface/node" class="pill pill--interface pill--normal-case pill--large" title="Go to INTERFACE Node"><code>Node</code></a>