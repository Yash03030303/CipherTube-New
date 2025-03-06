# CipherTube-New
This is Video Streaming Website which is also compatible with the mobile device with payment integration. This website allows users to upload, watch, and interact with videos. Premium members can access exclusive content

# Features
1. User Authentication
Register: Create a new account with a username, email, and password.
Login/Logout: Securely log in and out of the platform.
Profile Management: Update bio and profile picture.

2. Video Management
Upload Videos: Upload videos with a title, description, and thumbnail.
Watch Videos: Stream videos with a built-in video player.
Premium Content: Only premium members can access exclusive videos.

3. Payment Integration
Razorpay Integration: Pay ₹1 to become a premium member.

4. Responsive Design
Built with Bootstrap for a clean and responsive UI.
Works seamlessly on all devices (desktop, tablet, mobile).

# Technologies Used

Backend:-
Django: Python-based web framework for backend logic.
Razorpay: Payment gateway for premium membership.
SQLite: Default database for development.

Frontend
HTML/CSS: For structuring and styling the website.
Bootstrap: For responsive design and pre-built components.
JavaScript: For dynamic interactions (e.g., Razorpay payment popup).

Other Tools
Font Awesome: For icons (e.g., profile, messages, comments).
Django Crispy Forms: For rendering forms beautifully.


# Setup Instructions
1. Clone the Repository
git clone https://github.com/your-username/video-sharing-website.git
cd video-sharing-website

3. Set Up a Virtual Environment
python -m venv venv
source venv/bin/activate
On Windows: venv\Scripts\activate

4. Install Dependencies
pip install -r requirements.txt

5. Set Up the Database
python manage.py migrate

6. Run the Development Server
python manage.py runserver


# Configuration:-

1. Razorpay Keys
Add your Razorpay API keys to settings.py:
RAZORPAY_KEY_ID = 'your_razorpay_key_id'
RAZORPAY_KEY_SECRET = 'your_razorpay_key_secret'

2. Static and Media Files
Static files (CSS, JS) are served from the static/ directory.
Media files (videos, thumbnails) are stored in the media/ directory.


# Contributing:-
Contributions are welcome! Follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature/YourFeatureName).
3. Commit your changes (git commit -m 'Add some feature').
4. Push to the branch (git push origin feature/YourFeatureName).
5. Open a pull request.
