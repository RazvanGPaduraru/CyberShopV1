# 🛒 CyberShopV1

**CyberShopV1** is a full-stack **online shop web application** built
with:

-   ⚛️ **React** (Frontend)
-   🔷 **ASP.NET (.NET / C#)** (Backend)

The project follows a **layered architecture**, separating domain
models, business logic, and data access into distinct projects for
maintainability and scalability.

------------------------------------------------------------------------

## 🚀 Features

-   Modern **React frontend** using contemporary UI libraries
-   **ASP.NET Web API** backend
-   Clean **domain-driven architecture**
-   Separate **Admin Console Application**
-   Modular **Visual Studio solution structure**
-   RESTful API communication between frontend and backend

------------------------------------------------------------------------

## 📁 Project Structure

    CyberShopV1/
    ├── CyberShop.Web.Client/        # React frontend
    ├── CyberShop.Web/               # ASP.NET Web API
    ├── CyberShop.Data/              # Data access layer
    ├── CyberShop.Domain.Models/     # Domain models
    ├── CyberShop.Domain.Logic/      # Business logic
    ├── AddAdminConsollApp/          # Admin console app
    ├── CyberShop.sln                # Visual Studio solution
    └── .gitignore

------------------------------------------------------------------------

## ✅ Prerequisites

Make sure you have the following installed:

-   .NET SDK
-   Node.js & npm
-   Visual Studio or VS Code

------------------------------------------------------------------------

## 🛠️ Setup & Run

### 1️⃣ Clone the Repository

``` bash
git clone https://github.com/RazvanGPaduraru/CyberShopV1.git
cd CyberShopV1
```

------------------------------------------------------------------------

### 2️⃣ Run the Backend

#### Using .NET CLI

``` bash
dotnet restore
dotnet build
dotnet run --project CyberShop.Web
```

#### Using Visual Studio

1.  Open `CyberShop.sln`
2.  Set `CyberShop.Web` as the startup project
3.  Click **Run**

------------------------------------------------------------------------

### 3️⃣ Run the Frontend

``` bash
cd CyberShop.Web.Client
npm install
npm run build-dev
npm run dev-watch
```

> ⚠️ Make sure the frontend API base URL matches the backend running
> port.

------------------------------------------------------------------------

## 🧩 Technologies Used

### 🎨 Frontend

-   React
-   TypeScript
-   Axios
-   Material-UI
-   Bulma

------------------------------------------------------------------------

### 🔧 Backend

-   ASP.NET (.NET / C#)

------------------------------------------------------------------------

### ⚙️ Build Tools

-   Webpack
-   Babel
