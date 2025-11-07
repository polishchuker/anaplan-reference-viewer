# anaplan-reference-viewer
Turns Anaplan “Referenced By” text into a clean and readable table of module and line item references. Helps with impact analysis and debugging. No login, no backend, runs in the browser.


# 🔍 Anaplan Reference Viewer

When working in Anaplan, the **"Referenced By"** column often becomes hard to navigate — especially when a line item is referenced across many modules. Anaplan displays these references as a long, comma-separated text string, which can be difficult to read and easy to misinterpret.

This tool provides a **clean, structured view** of that information, making it easy to understand dependencies and trace calculation flows in your model.

---

## ✅ What This Tool Does

- Takes the **raw** "Referenced By" text copied from Anaplan
- Automatically separates entries into:
  - **Module Name**
  - **Line Item Name**
- Displays the results in a **clean, sortable table**
- Helps avoid missed references and improves model transparency

---

## 🎯 Why This Helps

| Without This Tool | With This Tool |
|------------------|----------------|
| Hard-to-read, comma-separated text | Organized table format |
| Easy to overlook dependencies | Clear visibility into all relationships |
| Slower debugging and auditing | Faster model impact analysis |
| Manual copy/paste into documents | Runs instantly in your browser |

---

## 🖥️ How to Use

1. Open the tool in your browser (host online or open the HTML file locally)
2. In Anaplan, open the **Blueprint** for a module
3. Copy the **Referenced By** field of a line item
4. Paste the text into the viewer
5. Click **Parse** — done ✅

---




