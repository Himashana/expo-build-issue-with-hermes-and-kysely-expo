# expo-build-issue-with-hermes-and-kysely-expo

This sample project is a clone of the sample code given in https://github.com/mphill/kysely-expo.git, which was only created to reproduce the Expo Cloud build failing issue when you are using kysely-expo and Hermes JS engine in Expo SDK 54 (latest).

## Key changes:
1. Migrated from yarn to pnpm.
2. Removed the line `plugins: [["@babel/plugin-transform-private-methods", { loose: true }]],` from the babel.config.js
