Previously, development was focused around Tauri, but this introduced several issues:
- Tauri mobile landscape is immature, so there is no fundamental plugins available, like SQL with SQL-cypher.
- I'm not familiar with Rust and I can not utilize Rust-backend, which is the main advantage of Tauri.

In contrast, capacitor seem to have all necessary plugins available:
- SQL + Cypher https://github.com/capacitor-community/sqlite
- PouchDb adapter with `capacitor-community/sqlite` https://github.com/BingCoke/pouchdb-adapter-sqlite
- PouchDb https://pouchdb.apache.org/
- File saver Dialog https://github.com/odion-cloud/capacitor-mediastore/issues/3 or proposed better workaround: https://github.com/capawesome-team/capacitor-plugins/issues/37#issuecomment-6018328374

With those plugins, readily available I will be able to move faster and easily implement core features of savnote