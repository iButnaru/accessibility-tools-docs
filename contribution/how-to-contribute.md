# 👨‍💻 How to contribute

### Getting Started

1. Fork the repository and clone your fork locally
2. Follow the setup instructions provided in the [**README**](https://git.clymio.com/dev-tools/a11y/-/blob/feature/dev-1637/README.md)

### Branching <a href="#user-content-branching" id="user-content-branching"></a>

* Create a new branch from master for any of your work
* Use the following naming convention for the branches:
  * feature/xyz (for features)
  * bugfix/xyz (for bugs)

### Development Standards <a href="#user-content-development-standards" id="user-content-development-standards"></a>

*   **Code Style**: Use Prettier/ESLint for consistent formatting. Run the following command before each commit:

    ```
    npm run lint
    ```
* **Small, Focused changes**: Keep PRs focused on a single topic. Smaller PRs are easier to review
* **Documentation**: Update the README or any of the other docs if your changes setup, usage or architecture

### Database Changes <a href="#user-content-database-changes" id="user-content-database-changes"></a>

**Accessibility Tools** uses Sequelize + SQLite to manage the database. The folder structure for the database related files is as follows:

* src/electron/db/
  * models/ : stores all the sequelize models that are translated into sqlite tables
    * system/ : stores all the system models. The tables created are prefixed with `system_`
  * migrations/ : stores sequelize migration files

For any updates to the database structure, the following steps need to be followed:

1. Create a new migration file under src/electron/db/migrations/. This file should have an incremental version based on the existing migration files
2. Update the relevant model files under src/electron/db/models/.
3. Update the package.json version.
4.  Run the app using:

    ```
    npm run dev
    ```

    This will run the migration file, sync the models and update the system data locally, if there are any changes there.

### Pull Request Process <a href="#user-content-pull-request-process" id="user-content-pull-request-process"></a>

1. Push your branch
2. Open a Pull Request (PR) to master
3. Respond to review feedback promptly
4. Your PR will be merged once it's approved and passes CI checks

### Community <a href="#user-content-community" id="user-content-community"></a>

All contributors are expected to follow our [**Code of conduct**](code-of-conduct.md) to ensure a welcoming environment for everyone.
