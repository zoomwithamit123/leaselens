LeaseLens/
│
├── backend/
│   ├── package.json
│   ├── server.js
│   ├── /routes
│   │   ├── auth.js
│   │   ├── properties.js
│   │   ├── tenants.js
│   │   ├── leases.js
│   │   ├── payments.js
│   │   └── maintenance.js
│   ├── /controllers
│   │   ├── authController.js
│   │   ├── propertyController.js
│   │   ├── tenantController.js
│   │   ├── leaseController.js
│   │   ├── paymentController.js
│   │   └── maintenanceController.js
│   ├── /middleware
│   │   └── authMiddleware.js
│   └── /models
│       ├── user.js
│       ├── property.js
│       ├── tenant.js
│       ├── lease.js
│       ├── payment.js
│       └── maintenance.js
│
├── frontend/
│   ├── package.json
│   ├── tailwind.config.js
│   └── src/
│       ├── index.js
│       ├── App.js
│       ├── /components
│       │   ├── Dashboard.js
│       │   ├── PropertyList.js
│       │   ├── TenantList.js
│       │   ├── LeaseList.js
│       │   ├── PaymentForm.js
│       │   └── MaintenanceList.js
│       └── /services
│           └── api.js
│
└── README.md
