# ArtistPedia

ArtistPedia is a comprehensive Android application designed to empower artists to showcase, share, and sell their artwork. The app aims to provide a vibrant, inclusive community for artists and art lovers, supporting a wide range of art forms including painting, sketching, sculpture, micro-art, calligraphy, and paper cutting. ArtistPedia bridges the gap between creators and admirers, making it easier for artists to reach a global audience and monetize their talent.

## Table of Contents
- [About](#about)
- [Mission & Vision](#mission--vision)
- [User Roles](#user-roles)
- [Features](#features)
- [App Structure](#app-structure)
- [How It Works](#how-it-works)
- [Getting Started](#getting-started)
- [Build & Installation](#build--installation)
- [Technical Stack & Dependencies](#technical-stack--dependencies)
- [Community & Safety](#community--safety)
- [Contributing](#contributing)
- [Future Roadmap](#future-roadmap)
- [Credits](#credits)

## About
One of the best places to display your artistic talent.

**ArtistPedia** was developed in 2022 by Palak Jagani and Amisha Maniya as a Bachelors final year project. The app aims to help artists sell their art, explore new ideas, and connect with a diverse group of people who all share creativity and originality in their own way—be it through sketching, painting, or micro-art. ArtistPedia is a platform where creativity meets opportunity.

## Vision
- **Vision:** To become the go-to global community for artists and art enthusiasts, fostering creativity, collaboration, and commerce in a safe and inclusive environment.

## User Roles
- **Artists/Buyers:**
  - Register, create a profile, upload and manage artwork, explore and purchase art, provide feedback, and interact with the community.
- **Admins:**
  - Manage users and posts, moderate content, send notifications, and oversee platform safety and quality.

## Features
- **User Registration & Profile Management:**
  - Sign up, log in, and manage personal profiles with bio, contact info, and profile pictures.
- **Artwork Upload & Showcase:**
  - Artists can upload images of their artwork, add descriptions, set prices, and categorize their creations.
- **Explore & Search:**
  - Browse and search for art by category (Sculpture, Painting, Sketch, Micro Art, Calligraphy, Paper Cutting Art) or artist.
- **Buy & Sell Artwork:**
  - Securely purchase artwork directly from artists. Artists can manage their sales and buyers can track their orders.
- **Feedback & Rating System:**
  - Users can provide feedback and rate artworks, helping others discover quality content.
- **Admin Panel:**
  - Admins can manage users, moderate posts, send push notifications, and access analytics via integrated Firebase tools.
- **Push Notifications:**
  - Real-time updates for new artwork, messages, and platform announcements using Firebase Cloud Messaging.
- **No-Internet Handling:**
  - User-friendly dialogs and offline handling to ensure a smooth experience even with connectivity issues.
- **Multi-language Support:**
  - The app supports multiple languages, making it accessible to a global audience.
- **Community Guidelines:**
  - Strict policies to ensure a safe, inclusive, and harassment-free environment for all users.

## App Structure
- **Home:** Main feed with trending and new artworks.
- **Profile:** User's personal gallery, bio, and account settings.
- **Upload:** Interface for adding new artwork.
- **Categories:** Explore art by type.
- **Admin:** Tools for moderation, user management, and notifications.
- **Feedback:** Submit feedback or report issues.

## How It Works
1. **Sign Up:** Create an account as an artist or buyer.
2. **Set Up Profile:** Add your bio, contact info, and profile picture.
3. **Upload Art:** Artists can upload artwork, set prices, and categorize their pieces.
4. **Explore & Buy:** Browse the gallery, search by category, and purchase art securely.
5. **Feedback:** Leave ratings and feedback for artists and artworks.
6. **Admin Tools:** Admins manage users, posts, and platform notifications.

## Getting Started
### Prerequisites
- Android Studio (latest recommended)
- Android SDK 33+
- Java 8+
- Firebase account (for authentication, database, and storage)

### Setup
1. **Clone the repository:**
   ```bash
   git clone <repo-url>
   ```
2. **Open in Android Studio:**
   - Open `Artistpedia/Artistpedia` as a project.
3. **Firebase Setup:**
   - Add your `google-services.json` to the `app/` directory (already present for development, replace with your own for production).
   - Configure Firebase Authentication, Realtime Database, and Storage in the Firebase console.
4. **Build the project:**
   - Sync Gradle and build the app.
5. **Run on device/emulator:**
   - Deploy the app to your Android device or emulator.

## Build & Installation
- Minimum SDK: 21 (Android 5.0 Lollipop)
- Target SDK: 33
- Build system: Gradle
- To build a release APK, use:
  ```bash
  ./gradlew assembleRelease
  ```

## Technical Stack & Dependencies
- **Languages:** Java, XML
- **Frameworks:** Android SDK, Firebase
- **Libraries:**
  - Android Support Libraries (AppCompat, Design, RecyclerView, CardView)
  - Firebase (Auth, Database, Storage, Messaging)
  - FirebaseUI
  - Glide, Picasso (image loading)
  - Retrofit, OkHttp (networking)
  - ButterKnife (view binding)
  - MaterialEditText, CircleImageView, InfiniteCycleViewPager, LikeButton, Card Form, Country Code Picker, etc.
- See `app/build.gradle` for the full list.

## Community & Safety
- **Inclusivity:** ArtistPedia welcomes artists of all backgrounds and skill levels. Discrimination, harassment, or exclusion of any kind is strictly prohibited.
- **Moderation:** Admins monitor content and user activity to ensure compliance with community guidelines.
- **Reporting:** Users can report inappropriate content or behavior for review by admins.
- **Privacy:** User data is handled securely using Firebase Authentication and Database rules.

## Contributing
Contributions are welcome! Please open issues or submit pull requests for improvements and bug fixes. Suggestions for new features and enhancements are encouraged.

## Future Roadmap
- Add in-app chat and messaging between users
- Expand payment options and integrate with more payment gateways
- Add support for video and multimedia art
- Implement advanced analytics for artists
- Launch iOS and web versions
- Community events and virtual exhibitions

## Credits
- Developed by Amisha Maniya and Palak Jagani
- Special thanks to all open-source library authors and contributors

---
*ArtistPedia: A community for every artist.* 