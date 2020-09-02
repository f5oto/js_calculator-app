# calculator-app
Simple calculator app

This is a simple calculator app uses vuln components

1. Enable the "npm bearer login realm"
<code> NXRM settings > Realms > npm bearer token realm > Add > Save</code>

2. Configure your nexus repo (group for example with proxy as a member)
   OPTIONAL: You can enable FW capability to demo failure of lodash

3. Set the npm proxy via command line:
<code>npm config set proxy http://localhost:8081/repository/npm-group/</code>

4. log in to npm realm:
<code>npm login</code>

5. Navigate inside the application folder and run:
<code>npm install</code>

This will proxy the components from nxrm and install/build the application.
