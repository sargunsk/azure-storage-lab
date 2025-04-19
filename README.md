# 📦 Azure Storage Lab – Blob, File & Lifecycle Management

This lab demonstrates how to work with Azure Storage using the free tier, focusing on Blob Storage, access tiers, file uploads/downloads, and lifecycle management. This simulates real-world cloud storage scenarios for backup, archival, and access optimization.

---

## 🧰 Technologies Used

- Microsoft Azure Portal
- Azure Storage (Blob)
- Azure Storage Explorer (optional)
- Access Tiers: Hot, Cool, Archive
- Lifecycle Management Rules

---

## ✅ What Was Done

- Created a storage account: `sargunstorage01`
- Created a private blob container: `mycontainer`
- Uploaded files via Azure Portal and/or Storage Explorer
- Tested download of uploaded files
- Changed access tier of blob to `Cool`
- Configured a lifecycle rule to move blobs to Cool tier after 30 days

---

## 🖼️ Screenshots

All screenshots are stored in `/screenshots/` folder:
- Storage account overview
- Blob container creation
- File uploaded and visible
- Access tier changed to Cool
- Lifecycle rule configuration

---

## 📁 Project Structure

azure-storage-lab/ ├── README.md ├── notes.txt └── screenshots/ ├── storage-account-overview.png ├── blob-container-created.png ├── file-uploaded.png ├── change-access-tier.png ├── lifecycle-rule.png


---

## 📝 Notes

This lab reflects a practical cloud storage use case. It demonstrates managing blob data efficiently using tiering and automation through lifecycle policies — critical skills in modern cloud operations.

---

## 📬 Author

**Sargun Kaur**  
GitHub Projects 