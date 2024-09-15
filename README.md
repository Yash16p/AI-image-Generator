### AI Image Generator (MERN + DALLE)
![Alt text](https://github.com/Yash16p/AI-image-Generator/blob/master/client/public/genai.png)

This project is an AI-powered image generator website built using the MERN stack (MongoDB, Express, React, Node.js) that integrates with OpenAI's DALLE model to generate unique images based on user inputs. The website is responsive and can be used on mobile devices as well.

Features
AI-powered image generation: Generate images using OpenAI's DALLE model.
Mobile-friendly design: The website is responsive and works seamlessly on mobile devices.
Real-time feedback: See the generated image in real-time after submitting your input.
User-friendly interface: Simple and intuitive interface for generating images.
Tech Stack
Frontend: React.js
Backend: Node.js with Express
Database: MongoDB
AI Model: DALLE by OpenAI
Deployment: Mobile and desktop-compatible
Installation
Prerequisites
Node.js (v14.19.1 or above)
MongoDB (local or cloud instance)
OpenAI API Key (for accessing DALLE)
Steps to Run Locally
Clone the repository:

bash
Copy code
git clone https://github.com/Yash16p/ai-image-generator.git
cd ai-image-generator
Install dependencies:

For the backend (in the root directory):

bash
Copy code
npm install
For the frontend (navigate to the client folder):

bash
Copy code
cd client
npm install
Set up environment variables: Create a .env file in the root directory and add the following:

bash
Copy code
MONGO_URI=your_mongodb_connection_string
OPENAI_API_KEY=your_openai_api_key
Start the development server:

Backend:
bash
Copy code
npm run server
Frontend (in a separate terminal window):
bash
Copy code
cd client
npm start
The website should now be running at http://localhost:3000.

Usage
Navigate to the website.
Enter a prompt describing the image you want to generate.
Click "Generate" and watch as DALLE creates an image based on your input.
View the generated image and download or share it as needed.
Screenshots
Homepage with image input field

Example of generated image result

Mobile View
The website is fully optimized for mobile devices, providing a seamless experience across different screen sizes.

Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.
