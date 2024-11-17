# 🌟 Çukurova University 1.5 Adana Student Teams Website

## Project Overview
Welcome to the GitHub repository for the Çukurova University 1.5 Adana Student Teams website. This project showcases the achievements, members, sponsors, and more of various student teams within the university. The website was built using HTML, CSS, and Bootstrap, and is deployed on Firebase to provide a modern and visually appealing platform for these student-led initiatives.

## Important Note
- This project is intended for educational purposes only and is not intended for commercial use.
- The website is currently under development and may not be fully functional or up-to-date.
- Paragraphs, images, and other content may be subject to change, as the project is currently in development.

## Features
- **Home Page**: An introduction to all the student teams (“Takım 1” to “Takım 5”) involved in the project, with easy navigation links to each team's details.
- **Team-Specific Pages**: Each team has dedicated pages that include:
  - **Anasayfa**: Introduction to the team, including highlights and visuals.
  - **Takım Üyeleri**: Details on each team member and their roles.
  - **Danışmanlar**: Profiles of the advisors helping the teams.
  - **Sponsorlar**: A showcase of sponsors supporting the team.
  - **Portfolyo**: Projects and products developed by the team.
  - **Başarılar**: Key achievements and awards earned by the team.
  - **İletişim**: Contact information for reaching the team.

The website features a clean and responsive design optimized for both desktop and mobile devices.

## Technologies Used
- **HTML & CSS**: Core technologies used for website structure and styling.
- **Bootstrap 5**: Utilized for responsive design, making the website compatible across different devices and screen sizes.
- **JavaScript**: Basic JavaScript for UI interactions.
- **Firebase**: The site is hosted and deployed using Firebase.

## Project Structure
The project follows a simple and organized folder structure:
```
/
|-- index.html
|-- assets/
    |-- images/
|-- teams/
    |-- team1/
        |-- team1_home.html
        |-- team1_members.html
        |-- team1_advisors.html
        |-- team1_sponsors.html
        |-- team1_portfolio.html
        |-- team1_achievements.html
        |-- team1_contact.html
    |-- team2/...
    |-- team3/...
    |-- team4/...
    |-- team5/...
```
- **index.html**: Landing page showcasing all teams.
- **teams/team1/**: Folder containing the HTML files for each section of team 1.

## Firebase Deployment
The project has been deployed using Firebase Hosting. To view the deployed site or make changes, follow these steps:

### Deploying to Firebase
1. Ensure you have the Firebase CLI installed. If not, install it:
   ```sh
   npm install -g firebase-tools
   ```
2. Authenticate with Firebase:
   ```sh
   firebase login
   ```
3. Initialize Firebase in the project directory:
   ```sh
   firebase init
   ```
   Choose **Hosting** and select the appropriate project.
4. Deploy the site:
   ```sh
   firebase deploy
   ```

### Firebase Configuration
Firebase configuration is defined in the `index.html` file:
```javascript
const firebaseConfig = {
  apiKey: "{API_KEY}",
  authDomain: "{AUTHDOMAIN}",
  projectId: "{PROJECTID}",
  storageBucket: "{STORAGEBUCKET}",
  messagingSenderId: "{MESSAGINGSENDERID}",
  appId: "{APPID}"
};
```
Replace placeholders with your actual Firebase project details.

## How to Use
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/student-teams-website.git
   ```
2. Open `index.html` in your preferred web browser to explore the site locally.

## Contributing
We welcome contributions to improve the project! Here are some ways to get involved:
- **Bug Reports & Feature Requests**: Use the [issues page](https://github.com/yourusername/student-teams-website/issues) to report bugs or suggest new features.
- **Pull Requests**: Fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any questions or suggestions, please reach out to the team via the [contact page](teams/team1/team1_contact.html) or through our [social media](https://www.instagram.com/birbucukadanaev/).

---
We hope you find this website helpful in learning more about the amazing student teams at Çukurova University! Feel free to explore and contribute.

