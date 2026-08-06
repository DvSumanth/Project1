# Dega Venkata Sumanth — My Backend Tasks (DineOS)

Notice: This folder contains a **full copy** of the `backend/` directory so the entire app can run and boot cleanly without missing dependency errors. However, you **only own and should only edit** your assigned module folder(s): `backend/app/modules/auth/`, `backend/app/modules/operations/`.

## Your tasks

### Authentication & Authorization
- [ ] Login API
- [ ] Register API
- [ ] JWT Authentication
- [ ] OTP Verification
- [ ] MFA
- [ ] Roles & Permissions
- [ ] Session Management (list/revoke sessions)
- [ ] Email Verification
- [ ] Password Reset
- [ ] Staff Management (register/list/remove staff)

### Operations (Floor / Table / Section Management + Tips)
- [ ] Floor Management
- [ ] Table Section Management
- [ ] Dining Table Management
- [ ] Tips & Tip Allocation

## Notes specific to you
- Operations was previously unassigned and has now been added — it already has 9 live API routes in the codebase.

## Common responsibilities (everyone)
- [ ] Database Models
- [ ] Pydantic Schemas
- [ ] CRUD APIs
- [ ] Business Logic
- [ ] Validations
- [ ] Swagger Documentation
- [ ] Unit Testing
- [ ] Git Branch & Pull Request
- [ ] Code Review Fixes

## Running this locally
```bash
cd backend
pip install -r requirements.txt
# Configure .env (already pre-configured in this directory)
alembic upgrade head
uvicorn app.main:app --reload
```
Interactive Swagger API Documentation: http://127.0.0.1:8000/docs

## Git workflow
Suggested branch name: `feature/dega-venkata-sumanth-auth-operations`

Reminder: Only touch your own assigned module folder(s) in your PR to avoid merge conflicts with teammates editing shared files.