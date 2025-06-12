# Task 3 – Multi-Cloud Architecture (AWS + GCP)

## 🌐 Architecture Overview
This project demonstrates a simple multi-cloud setup where:
- **Frontend** is hosted on AWS S3
- **Backend** (API) is powered by Google Cloud Function

---

## 🔗 Public URLs
- **AWS S3 Website**: [Multi-Cloud Frontend](https://multi-cloud-frontend-mitesh.s3.ap-south-1.amazonaws.com/index.html?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAXYHSZFIJJYS7M4OM%2F20250612%2Fap-south-1%2Fs3%2Faws4_request&X-Amz-Date=20250612T094124Z&X-Amz-Expires=300&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBIaCmFwLXNvdXRoLTEiRjBEAiA32W%2Fiuqr3zFWVjGfYZcvvjKRPO4lgTg4ohdGPVvVxUQIgfGiR%2FUsrZP4euNa%2BZP29rb%2BtLKuxtOBttq531QqikZ4q3wII6%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAAGgw1MzMwODUxMDQ2NTgiDIS%2BWgs%2B6dSfe5znByqzAit2ukvOTXGBORMKDO09RaJPLPiKEqmkn%2Bxn790uYUMss08ERlXLc2jf8uaUGN9ztsOZH%2FGC5MhfmQuhD7R4cRTpxw%2BHUnSmp8g6hicpvwWOkz5QVH59nfKdoUqUhfFEM5T9KO8ouUXp5lM%2FjYn5hgRM5uvLMu%2BwHWi6e7BTVSKcj4ogmygwXNjKdlZz1oW73RogeSMyxB%2Fu5DoTqYern4Op2SWOWs%2Ba3dYtNgR6LitlVib3mEkevqqH9jLeWvy63panDYXH%2FnSDQPMk8dX3ORrQtNYIUHllVdNK2gaG7GUm89WdqDfLOqJ4G6K7ZjTSkrkyKZXyqjYJrQPSEktsaF9FKL4ajy9QR3mHCfy2EDbM23fNYDA43mygF9W%2BiErrm7Nmic4G29TRCTRAR15M2K2MTs4wxKeqwgY6rgKGFS4a9rC9Kq3LcsZ7DUsje%2FWk%2BNtWC8KkrFQ8gfnfCUnQnaw1MfICd%2FwS7Mi1i1BKy71rL67v1SQbj9LhOIBpt45sRxWUpC53qmGBeNXUsELXh6Iw1m1aoJv4NQ%2BKZ%2Bs4tzh5jjFyEEu6mFZ4qtYGWCm8qc0fpksvbAWKsAKdFsGlJl9nNjF00GkR8q6jzX6x1CRWKQ6gqrCoBdceejwHYO5p1nW6WJAKLeJfV3D04rwSjZ9eQFZUR3bCJ4%2BW3CPv%2B2oUB07t6HsMOfiMx0pS0fIGd2WXnmLlrv3joFp7AbifuJsr7FbJeiUTl%2B%2Fufq9RkV1OxJBloHv6G3KxPO4S%2FTu7QGkM3Lnzds9%2B4ooa4T6AOuWYOIMmIyOPvGy0CNBwYwhtspt7U5GK%2F%2FiTiw%3D%3D&X-Amz-Signature=30bf341188200470064f0b4e45bf829fb684c1adb252b60d7b1e522ed2e2e5a7&X-Amz-SignedHeaders=host&response-content-disposition=inline)
- **GCP Cloud Function**: [GCP API](https://asia-south1-root-dispatch-458612-b2.cloudfunctions.net/hello_world) (called via JS)

---

## 🛠️ Technologies Used
- AWS S3 (Static Website)
- Google Cloud Function (Python / Node.js)
- HTTPS API Call via `fetch()`
- CORS enabled in Cloud Function

---

## 📸 Screenshots
- ✅ S3 Bucket Configuration
- ✅ Cloud Function Console
- ✅ Browser Output (API response)
- ✅ Architecture Diagram (optional)

---

## 💡 Learning Outcomes
- Understood how to link two cloud providers
- Learned basics of serverless functions
- Managed public access securely using IAM and policies
- Used Free Tier resources from both platforms

---

## 🛡️ Cost Management
- S3 Storage < 5GB (Free Tier)
- Cloud Function < 2M calls/month (Free Tier)
- Function and bucket will be deleted after evaluation

---

**Submitted by:** Mitesh  
**Internship Program:** EliteTech – Cloud Computing  
