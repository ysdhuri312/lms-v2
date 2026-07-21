<!-- @format -->

# For Frontend

client/
├── src/
│ ├── app/ # Next.js routes
│ │ ├── dashboard/
│ │ ├── courses/
│ │ ├── login/
│ │ └── layout.tsx
│ │
│ ├── features/
│ │ ├── auth/
│ │ │ ├── components/
│ │ │ ├── hooks/
│ │ │ ├── api/
│ │ │ └── types.ts
│ │ │
│ │ ├── courses/
│ │ ├── payments/
│ │ └── dashboard/
│ │
│ ├── components/ # reusable UI
│ │ ├── ui/
│ │ ├── forms/
│ │ └── layout/
│ │
│ ├── lib/
│ │ ├── api-client.ts
│ │ ├── auth.ts
│ │ └── utils.ts
│ │
│ ├── store/
│ ├── hooks/
│ ├── types/
│ └── constants/

# For Backend

server/
├── src/
│ ├── modules/
│ │ ├── auth/
│ │ │ ├── auth.controller.js
│ │ │ ├── auth.service.js
│ │ │ ├── auth.repository.js
│ │ │ ├── auth.routes.js
│ │ │ ├── auth.validation.js
│ │ │ └── auth.schema.js
│ │ │
│ │ ├── users/
│ │ ├── courses/
│ │ ├── payments/
│ │ ├── enrollments/
│ │ └── admin/
│ │
│ ├── shared/
│ │ ├── middleware/
│ │ ├── utils/
│ │ ├── config/
│ │ ├── database/
│ │ └── constants/
│ │
│ ├── app.js
│ └── server.js
