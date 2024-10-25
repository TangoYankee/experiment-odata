Setup
1) Get the metadata file
  - The route to the portal is listed in 1Password under "Dynamics metadata file route"
  - Download the OData metadata file
2) Add the metadata file to the repository
  - Ensure the meta data file is named `ODataV4Metadata.xml`
  - Place the file in the root directory of this project
3) Checkout the correct version of node
  - `nvm use`
4) Install the required dependencies
  - `npm i`
5) Generate the resources
  - `npm run gen-odata`
