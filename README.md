# Smart Irrigation and Weather-Based Crop Recommendation System

## Project structure

- `frontend/` — UI source files for convenient editing: Thymeleaf HTML templates and static CSS/JavaScript.
- `backend/` — Spring Boot Java application, Maven `pom.xml`, configuration, database files, and the runtime copies of the templates/static assets.

## Important note about this project

This application uses Spring Boot with Thymeleaf, so the running application loads its pages and static assets from `backend/src/main/resources/templates` and `backend/src/main/resources/static`. Those original runtime files are kept in place so the backend continues to work. The `frontend/templates` and `frontend/static` folders are convenient copies for browsing/editing; when you change UI files, copy the changed files into the matching backend resource folder too, unless you later configure a build/sync workflow.

## Open in VS Code

1. Extract this ZIP.
2. In VS Code, choose **File → Open Folder**.
3. Select the main `smart_irrigation_and_wether_based_crop_recomendation_system` folder.
4. Expand `frontend` for UI files and `backend` for Java code.

## Run the backend

- Install a compatible JDK and Maven (or use the Maven wrapper if one is included).
- Open a terminal in `backend`.
- Run `mvn spring-boot:run` (Windows: `mvnw.cmd spring-boot:run` if a Maven wrapper is present).
- Alternatively, follow `backend/README.md` or use `backend/run.bat` if provided.

Do not commit real passwords, API keys, or other secrets.
