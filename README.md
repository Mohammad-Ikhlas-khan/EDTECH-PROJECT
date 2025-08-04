# StudyNotion – EdTech Platform

StudyNotion is a full-stack EdTech web application designed to facilitate online learning by enabling instructors to create and manage courses, and students to enroll and engage with educational content.



## 🚀 Features

**User Authentication:** Secure sign-up and login functionalities for both instructors and students.

**Course Creation & Management:** Instructors can create, update, and manage courses with ease.

**Enrollment System:** Students can browse available courses and enroll in those of interest.

**Responsive Design:** Optimized for various devices to ensure a seamless user experience.

**Modern UI/UX:** Clean and intuitive interface built with contemporary design principles.


## 🛠️ Tech Stack

**Frontend:**

*React.js*

*Tailwind CSS​*
*GitHub*

**Backend:**

*Node.js*

*Express.js​*

**Database:**

*MongoDB​*

## Project Structure 

```
EDTECH-PROJECT/

├── public/             # Static assets

├── server/             # Backend server code

├── src/                # Frontend source code

├── .editorconfig       # Editor configuration

├── .gitattributes      # Git attributes

├── .gitignore          # Git ignore file

├── .nvmrc              # Node version manager configuration

├── .prettierignore     # Prettier ignore file

├── README.md           # Project documentation

├── package.json        # Project dependencies and scripts

├── prettier.config.js  # Prettier configuration

└── tailwind.config.js  # Tailwind CSS configuration
```

## 📦 Installation

### 1.Clone the repository:
```bash
git clone https://github.com/Mohammad-Ikhlas-khan/EDTECH-PROJECT.git
```
### 2.Change the directory:
```
cd EDTECH-PROJECT
```

### 3.Setup Backend:
```
cd server
```
```bash
npm install
```
*Now create .env file inside the server folder*
```
# Mail Configuration
MAIL_HOST=smtp.gmail.com
MAIL_USER=your_email@gmail.com
MAIL_PASS=your_email_password_or_app_password

# JWT Secret
JWT_SECRET=your_jwt_secret

# Cloudinary Configuration
CLOUD_NAME=your_cloudinary_name
API_KEY=your_cloudinary_api_key
API_SECRET=your_cloudinary_api_secret

# Razorpay Keys
RAZORPAY_KEY=your_razorpay_key
RAZORPAY_SECRET=your_razorpay_secret

# MongoDB
MONGODB_URL=your_mongodb_connection_string

# Other
PORT=4000
```
### 4.Setup Frontend:
```
cd ../src
```
```bash
npm install
```
### 5.Run the Application:
**Run Backend**
```
cd ../server
```
```bash
npm run dev
```
*You should see your backend running on [http://localhost:4000].*

**Run Frontend**
```
cd ../src
```
```bash
npm start
```
*This will start the frontend on [http://localhost:3000].*

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.
