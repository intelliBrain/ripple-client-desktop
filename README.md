# Desktop Client

## Install Dependencies

- Clone the ripple-client-desktop repository
- Run `npm install`
- Run `npm install nw --nwjs_build_type=sdk --save-dev` (optional, needed only
  for development)

## Build

- In the ripple-client-desktop repository, make a copy of the
  `config_example.js` file and name it `config.js`
- Run `gulp` in your command line for development
- Run `gulp packages` in your command line for the production ready client
  - To build Windows executable in Linux, install `wine` and `winetricks` and
    install .Net 2.0 SP2 with `winetricks dotnet20sp2`.
- Your desktop client is in the `packages/RippleAdminConsole` directory
