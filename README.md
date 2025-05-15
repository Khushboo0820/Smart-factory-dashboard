# 🏭 Smart Factory Dashboard

A lightweight and responsive dashboard UI for monitoring smart factory production data. Built with **React**, **TypeScript**, **Mantine UI**, and supports basic internationalization.

## 🧩 Features

### 📊 Production Monitoring Dashboard
- **Responsive layout** using [Mantine UI](https://mantine.dev/)
- **Page title**: "Production Monitoring"
- **Filter Section**:
  - Machine Name input (select or text)
  - Date Range picker (Mantine DatePicker)

### 📈 Production Chart
- Displays **daily production count** using `Recharts` or `ApexCharts`
- Consumes **mock data** (static `.json` or via [Mocki.io](https://mocki.io/))
- Line or bar chart visualization

### 📋 Data Table
- Simple data table with Mantine's `<Table>` component
- Columns:
  - Machine Name
  - Status
  - Output
  - Last Updated

### 🔁 API Handling with React Query
- Simulates data fetching via mock APIs
- Displays **loading** and **error** states
- No caching or mutation logic required

### 🌐 Internationalization (i18n)
- Integrated `react-i18next` for language support
- Language switcher (dropdown/toggle)
- Translates:
  - Page title
  - Form labels
  - Table headers
- Supports: **English** and **Korean**

---

## 🚀 Tech Stack

- **React** (with Vite or CRA)
- **TypeScript**
- **Mantine UI**
- **Recharts / ApexCharts**
- **React Query**
- **react-i18next**

---

## 📦 Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/smart-factory-dashboard.git
   cd smart-factory-dashboard
2. **Install dependencies:**
   ```bash
   npm install
3. **Start the development server:**
   ```bash
   npm run dev
