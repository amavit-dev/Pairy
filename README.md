# Au Pair Connect - Community Communication Platform

A fully functional web application for female au pairs to connect, share experiences, and support each other through forum discussions and photo sharing.

## 🎨 Features

### User Features
- **User Authentication**: Separate login systems for users and administrators
- **User Registration**: Create new accounts with profile information
- **Forum Categories**: 
  - 🍳 Recipes - Share cooking tips and favorite recipes
  - 🗺️ Places to Go - Discover and recommend locations
  - 💼 Open Jobs - Find and post au pair opportunities
  - 👥 Group Hangout - Connect and organize meetups
- **Thread Management**: Create new discussion threads with titles and content
- **Photo Upload**: Share photos in threads and replies
- **Reply System**: Nested replies with threaded conversations
- **User Profiles**: View user information and activity

### Admin Features
- **User Management**: View, edit, and delete user accounts
- **Content Moderation**: Delete inappropriate threads and posts
- **Statistics Dashboard**: View platform metrics and activity
- **Recent Activity Monitoring**: Track user engagement

## 🎨 Design

- **Color Scheme**: Soft pastel pink theme throughout
- **Responsive Design**: Fully responsive for mobile, tablet, and desktop
- **Modern UI**: Clean, intuitive interface with smooth animations
- **Accessibility**: Semantic HTML and proper ARIA labels

## 📁 Project Structure

```
final/
├── index.html                  # Landing/login page
├── user-dashboard.html         # Main user interface
├── admin-dashboard.html        # Admin interface
├── css/
│   ├── main.css               # Global styles and variables
│   ├── auth.css               # Authentication page styles
│   └── forum.css              # Forum-specific styles
├── js/
│   ├── auth.js                # Authentication logic
│   ├── forum.js               # Forum functionality
│   ├── upload.js              # Photo upload handling
│   └── storage.js             # Data management (localStorage)
├── images/
│   ├── logo.png               # Application logo (400x400)
│   └── placeholders/          # Sample images
│       ├── avatar-1.png       # User avatar placeholder
│       ├── avatar-2.png       # User avatar placeholder
│       ├── avatar-3.png       # User avatar placeholder
│       ├── avatar-4.png       # User avatar placeholder
│       ├── avatar-5.png       # User avatar placeholder
│       ├── recipe-sample.png  # Recipe photo placeholder
│       ├── location-sample.png # Location photo placeholder
│       └── group-sample.png   # Group photo placeholder
└── README.md                  # This file
```

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No server required - runs entirely in the browser using localStorage

### Installation
1. Download or clone the project files
2. Open `index.html` in your web browser
3. Start using the application!

### Demo Accounts

#### Admin Account
- **Email**: admin@aupair.com
- **Password**: admin123

#### Sample User Accounts
- **Maria Schmidt**: maria.schmidt@email.com / password123
- **Sophie Laurent**: sophie.laurent@email.com / password123
- **Anna Kowalski**: anna.kowalski@email.com / password123
- **Lisa Müller**: lisa.muller@email.com / password123
- **Emma Wilson**: emma.wilson@email.com / password123

## 📊 Sample Data

The application comes pre-loaded with demonstration data:

### Forum Content
- **15 Discussion Threads** across all categories
- **91 Posts and Replies** with realistic conversations
- **5 Sample Users** with complete profiles
- **Varied Topics**: Recipes, travel tips, job advice, meetup planning

### Categories Distribution
- Recipes: 4 threads
- Places to Go: 4 threads
- Open Jobs: 3 threads
- Group Hangout: 4 threads

## 🎯 Key Functionality

### User Flow
1. **Register/Login** → Create account or sign in
2. **Browse Categories** → Select a forum category
3. **View Threads** → Read discussions
4. **Create Thread** → Start new conversations
5. **Reply** → Participate in discussions
6. **Upload Photos** → Share images with posts
7. **Logout** → Secure session management

### Admin Flow
1. **Admin Login** → Access admin dashboard
2. **View Statistics** → Monitor platform metrics
3. **Manage Users** → Edit or remove user accounts
4. **Moderate Content** → Delete inappropriate threads/posts
5. **Monitor Activity** → Track recent user actions

## 💻 Technical Details

### Technologies Used
- **HTML5**: Semantic markup
- **CSS3**: Custom properties, flexbox, grid, animations
- **Vanilla JavaScript**: No frameworks or libraries
- **localStorage**: Client-side data persistence
- **Responsive Design**: Mobile-first approach

### Browser Compatibility
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

### Responsive Breakpoints
- **Mobile**: 480px and below
- **Tablet**: 481px - 768px
- **Desktop**: 769px and above

## 🎨 Color Palette

```css
Primary Pink: #FFB6C1
Light Pink: #FFE4E9
Pale Pink: #FFF0F3
Medium Pink: #FF9EAD
Dark Pink: #FF8FA3
```

## 📝 Features Implementation

### Authentication System
- User registration with validation
- Separate user and admin login
- Session management
- Password visibility toggle
- Remember me functionality

### Forum System
- Category-based organization
- Thread creation with rich content
- Nested reply system
- View counter
- Reply counter
- Timestamp formatting (relative time)

### Photo Upload
- Multiple photo upload support
- Image preview before posting
- Photo gallery display
- Responsive image sizing
- Remove photo functionality

### Admin Dashboard
- User statistics
- Thread and post counts
- Recent activity feed
- User management table
- Content moderation tools

## 🔒 Security Notes

**Important**: This is a demonstration application using localStorage. For production use:
- Implement proper backend authentication
- Hash passwords (currently stored in plain text)
- Use secure session management
- Implement CSRF protection
- Add input sanitization
- Use HTTPS
- Implement rate limiting

## 📱 Responsive Design

The application is fully responsive with:
- Mobile-friendly navigation (hamburger menu)
- Touch-optimized buttons and inputs
- Flexible layouts that adapt to screen size
- Optimized typography for readability
- Proper spacing on all devices

## 🎯 Future Enhancements

Potential improvements for production:
- Backend API integration
- Real-time messaging
- Email notifications
- Advanced search functionality
- User profile customization
- Private messaging
- File attachments (documents, videos)
- Multi-language support
- Dark mode theme

## 📄 License

This is a demonstration project for educational purposes.

## 👥 Credits

Developed as a community platform for au pairs to connect and support each other.

---

**Version**: 1.0.0  
**Last Updated**: December 2025  
**Status**: Complete and Ready for Demonstration
