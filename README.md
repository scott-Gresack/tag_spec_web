# 🌐 Web Tag Spec Builder

The **Web Tag Spec Builder** is a dynamic tool designed to streamline the creation of tag specifications for the Adobe Web SDK. It allows users to quickly generate payloads for `utag.view()` or `utag.link()` events, along with their corresponding XDM (Experience Data Model) objects, saving time and reducing errors during implementation.

---

## 🚀 Purpose

This tool helps engineers, analysts, and QA testers by automating the generation of tag specs and XDM payloads. With a focus on accuracy and efficiency, the Web Tag Spec Builder ensures that Adobe Web SDK integrations are smooth, consistent, and easy to validate.

---

## 🛠 Features

1. **Dynamic Payload Generation**:
   - Supports both `utag.view()` and `utag.link()` event types.
   - Allows users to define key-value pairs and map them to `eVars`, `props`, or events.

2. **XDM Object Visualization**:
   - Provides a preview of the corresponding XDM object structure for Adobe Web SDK.

3. **Intuitive UI**:
   - Interactive, easy-to-use interface with responsive design.
   - Built-in copy functionality to quickly use generated snippets.

4. **Error-Free Implementation**:
   - Reduces manual errors by automating payload creation.
   - Aligns with Adobe Web SDK standards.

---

## 🛠 Instructions for Use

1. **Select the Event Type**:
   - Choose between `utag.view()` and `utag.link()` using the dropdown menu.

2. **Add Key-Value Pairs**:
   - Enter the key (e.g., `page_name`) and value (e.g., `homepage`) for your event.
   - Map the key to an `eVar`, `prop`, or event as needed.

3. **Preview the Outputs**:
   - View the dynamically generated tag spec (`utag.view()`/`utag.link()`).
   - See the corresponding XDM object for Adobe Web SDK.

4. **Copy and Use**:
   - Use the "Copy" buttons to copy the generated code snippets for implementation or testing.

5. **Reset as Needed**:
   - Easily clear the form and start over if required.

---

## 🎯 Benefits for Stakeholders

### **Engineers**:
- **Save Time**: Automate the creation of tag specs.
- **Ensure Accuracy**: Minimize human error during implementation.
- **Debugging**: Use the XDM object preview to validate network requests in the browser.

### **Analysts**:
- **Streamline Reporting**: Ensure all required variables (`eVars`, `props`, events) are mapped correctly.
- **Align Goals**: Collaborate effectively with engineering teams to meet reporting requirements.

### **QA Testers**:
- **Validate Payloads**: Use generated tag specs to verify network requests in tools like the browser's developer console.
- **Debug Efficiently**: Ensure mappings are correct before release.

### **Product Managers**:
- **Ensure Alignment**: Confirm that tracking requirements are met for key business goals.
- **Improve Collaboration**: Bridge the gap between engineering, analytics, and QA teams.

---

## 📄 Example Outputs

### **Tag Spec Example (`utag.view()`)**
```javascript
utag.view({
  page_name: "homepage",
  site_section: "products",
  site_language: "en"
});
