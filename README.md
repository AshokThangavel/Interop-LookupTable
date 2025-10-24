# Interop Lookup Table UI
This project is a **CSP-based web application** built for **InterSystems IRIS Interoperability** environments.  
It provides an easy-to-use web interface for creating, editing, and managing **Lookup Tables** directly within an interoperability-enabled namespace.

---

## 🚀 Features

- 🌐 Web-based UI for managing InterSystems IRIS lookup tables  
- 🧩 Namespace selection via dropdown (works across interoperability-enabled namespaces)  
- ➕ Create, edit, and delete lookup tables easily  
- 🔍 Quick search and pagination support  
- 💾 One-click save and cancel actions  
- 🧱 Built with CSP and InterSystems IRIS  

---

## ⚙️ Installation

Clone or download the repository:

```bash
git clone https://github.com/AshokThangavel/Interop-LookupTable.git
````

Build the Docker container:

```bash
docker compose --progress plain build
```

Start the container:

```bash
docker compose up -d && docker compose logs -f
```

Access the InterSystems IRIS **System Management Portal** at:

👉 [http://localhost:52773/csp/sys/UtilHome.csp](http://localhost:52773/csp/sys/UtilHome.csp)

---

## 💡 How to Use

1. Open the demo URL in your browser:
   👉 [http://localhost:52773/csp/user/Interop.LookUpTable.cls](http://localhost:52773/csp/user/Interop.LookUpTable.cls)

2. Select an interoperability-enabled namespace from the **dropdown** (e.g., `LEARNING`).

3. Use the sidebar to view available lookup tables.

4. Add, edit, or delete lookup table entries:

   * **Add New** → create a new key/value pair
   * **Delete Selected** → remove selected entries
   * **Save Changes** → persist updates to IRIS

5. All changes are reflected in the corresponding IRIS interoperability lookup tables.

---

## 🖼️ Screenshot

Below is a sample view of the Lookup Table UI:
<img width="1245" height="817" alt="image" src="https://github.com/user-attachments/assets/2bdc3067-9658-43ac-9390-bd12a1a32bfb" />


---

## 📄 License

This project is distributed under the **MIT License**.
Feel free to use, modify, and contribute!

---

