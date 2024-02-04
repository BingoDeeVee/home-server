# home-server

TODO:
- [x] Create env files for compose files
- [x] Add root directory key to env files
- [ ] Create Github secrets
- [ ] Write build steps to create secret files

Notes:
- The `env_file` and `.env` root file are different concepts. For using interpolated variables in the docker compose file, create a `.env` file for all your variables across all compose files. Seperate them out with commented sections if you like.