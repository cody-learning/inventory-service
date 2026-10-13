# inventory-service

Go + React application using **AWS CDK** for infrastructure.

## Structure
- `backend/` — Go Chi API
- `frontend/` — React (Vite)
- `infra/` — CDK app (TypeScript)
- `buildspec.yml` — CodeBuild example

## Deploy
```bash
cd infra
npm install
npx cdk deploy
```
