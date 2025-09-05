# permitrouteplanner
Blazor Server app to create/manage OS/OW permit requests with route mapping and PDF export.

A small demo app that mirrors an **Oversize/Overweight (OS/OW) permit** workflow: create a permit request, capture vehicle specs, draw/display a route on a map, store records in **MSSQL**, and export a simple PDF summary. Built to showcase fit for roles working on DOT routing & permitting portals with a focus on **UI/UX**, **accessibility**, and **SQL**.

---

## ✨ Features
- **Permits CRUD**: Create, list, and edit permits (permit #, carrier, origin/destination, vehicle dimensions, gross weight).
- **MSSQL data store** with a simple schema and a lightweight repository using **Dapper**.
- **Map & route**: Display or draw a route with **Leaflet** via Blazor **JS interop**.
- **PDF export (optional)**: Generate a one-page permit summary (swap-in Syncfusion PDF or any preferred PDF library).
- **Clean, accessible UI**: Responsive layout (Bootstrap), basic ARIA roles, and keyboard-friendly forms.
- **(Optional) Smoke test**: A single Selenium test that fills the form and asserts creation.

---

## 🧰 Tech Stack
- **.NET 6**, **Blazor Server**, **C#**
- **MSSQL** (SQL Server / LocalDB), **Dapper**
- **Visual Studio 2022**, **SSMS**
- **Bootstrap 5**, **Leaflet** (via JS interop)
- **Git** (compatible with Azure DevOps/TFS or any Git host)

---

