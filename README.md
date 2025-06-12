# Task 3 – Multi-Cloud Architecture (AWS + GCP)

## 🌐 Architecture Overview
This project demonstrates a simple multi-cloud setup where:
- **Frontend** is hosted on AWS S3
- **Backend** (API) is powered by Google Cloud Function

---

## 🔗 Public URLs
- **AWS S3 Website**: [Multi-Cloud Frontend](https://multi-cloud-frontend-mitesh.s3.ap-south-1.amazonaws.com/index.html?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=ASIAXYHSZFIJLXWNRDEM%2F20250612%2Fap-south-1%2Fs3%2Faws4_request&X-Amz-Date=20250612T101424Z&X-Amz-Expires=300&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBIaCmFwLXNvdXRoLTEiSDBGAiEAik6nSm6e4%2FRt3Fc55PYBXSccE86Gq1GVunHODOwlNnICIQCR57t%2BYFysrdxQ11%2FiXjSiHShhj%2BkhWgIlI5PYCGLeNyrfAgjr%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAAaDDUzMzA4NTEwNDY1OCIMpxXeSp94YvH7fyCMKrMCJegQV1aUtgCXbY9yKwGhbvVyWZQiTHftGDiPhXN9n7nTpTxTrE0ThkzSPaUj6cKuRNGLyNRLdQXjYBF%2F5%2FsiVhU8JaMK8At6fz3f2JALAe12OSXibhCg1Dfc%2BK6xrG5LwDJ4o2MbqsLC7f0k8kJyAKu67kfrw9wuZ603H32xpizJfks%2B63UiQIEbKr0EGFjgXmTKGjZT9AWZQdZZm9e4Pyxct7o3hXXUJ29%2F3Jz6nFFpbf21MUoxzkZWDFFBh6cV41NDbI0A92ssOW8wVizvBdR%2BacxqkwrZIcnHReWD5zLB2ig3I11BoK6G202TRG%2F3LAeEcuwpNBaC53k%2B79T2nT3HSblHHj%2FHd3wEFwm9eSnJtyWwvsbGM5y9pfeUTJ2P28uImv1C6bccT6eLGebEhNKupzDEp6rCBjqsAkM68Qfdku7pfBoOF5vxrXeKirWH%2FLyDrFozBoVyep3sMvSXFRkNvppjW4E5Gj5LVzHm7eFCxSmKPJZGZ%2F3MUs4aZCZBbMONE%2FxF%2ByoPb2P3NuC%2FqLVIPgZnPmFszQnlfLUstIDJ90srlHdGLLXN5wQLAUJ757bEjA4BRIzrFnLx8ddWVqMJ4xkhpNvPlgp6lRHtrAf3BxunHge%2F%2F1hVDxOg7yci%2B%2FOT0ViHmebRrC9CHIOYmuIXZmm6CdELfBfWR98QwkOp%2Fxnid%2FTjifoDyeZU3Aj7QtxYy0RDdAqDLpXgVqkB8OxVvVmd0bLjL46l7ld62ImkcV6jj4kWou3Ov%2FYxOtf2UY9GklyP3MIphK71KW9RlJIj6YL75S25Y9c4%2F7b3ztzLno584x6FDA%3D%3D&X-Amz-Signature=450f141ca2e61bfacdeb5f55a8543476c463c18296554f396d0b6e670f3b53a1&X-Amz-SignedHeaders=host&response-content-disposition=inline)
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
