# RT
Fashion Recommendation System
✨ Project Description
This project is a Pinterest-inspired fashion recommendation system that helps users discover similar outfits and accessories based on an uploaded image. The system:

Analyzes a user-uploaded outfit image

Finds visually similar Pinterest fashion pins

Extracts jewelry & accessories from those pins

Recommends purchasable items from e-commerce sites (Myntra, Ajio, etc.)

Built with Next.js, Google Cloud Vertex AI Matching Engine, and computer vision APIs, it provides personalized fashion inspiration with direct shopping links.

🚀 Features
✔ Image Upload – Users upload their outfit photos
✔ Theme Selection – Choose from aesthetic categories (Bohemian, Y2K, Minimalist, etc.)
✔ AI-Powered Matching – Finds similar Pinterest pins using vector similarity
✔ Accessory Detection – Identifies jewelry and fashion items
✔ E-commerce Integration – Recommends buyable products with affiliate links

🛠 Tech Stack
Category	Technologies
Frontend	Next.js, React, NextUI (UI Library)
Backend	Node.js, Next.js API Routes
AI/ML	Google Vertex AI Matching Engine, Computer Vision (TensorFlow.js/Cloud Vision)
Storage	Local file storage (for uploads)
APIs	Pinterest API, E-commerce Affiliate APIs


🔍 How It Works
1. User Uploads an Image
The frontend (ImageUploader.jsx) allows image selection and preview.

The image is sent to /api/upload and stored in public/uploads/.

2. User Selects a Theme
The frontend sends the theme (e.g., "Bohemian daydream") to /api/recommendation.

3. Backend Processes the Request
Generates an image vector (using vision.js).

Finds similar Pinterest pins (via matching.js & Vertex AI).

Extracts accessories (using object detection).

Searches e-commerce sites (via productSearch.js).

4. Returns Recommendations
Displays similar Pinterest outfits.

Shows buyable accessories with affiliate links.

📌 Future Improvements
🔹 User Accounts – Save favorite recommendations
🔹 Advanced Styling Tips – AI-generated fashion advice
🔹 Multi-Image Upload – Compare multiple outfits
🔹 Better Error Handling – Retry failed API calls

📜 License
MIT License.

💡 Contributors
ADITI GHOSH

🌟 Enjoy Styling!
Try it out and let AI help you find your next favorite outfit! 🛍️✨
