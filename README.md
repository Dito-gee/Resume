# Resume
### My Portfolio - Nderitu Githaiga - Painter and Decorator

### Site Overview
The online resume has been designed to fulfil a genuine need to make me be more accessible to recruiters and individuals interested in finding painter and decorators.

Whilst there are numerous painter and decorators, I have not yet come across a self-employed painter and decorator with an online presence / website except for small, medium and large painting and decorating businesses.

The reason behind this is to market myself more and therefore increase chances of getting work. Especially when you consider the current economic situation in the country. 
The website is designed to be responsive and accessible on a range of devices, making it easy to navigate for potential users.

![Screenshot 2025-06-25 184504](https://github.com/user-attachments/assets/30227fda-cd94-46c0-80a9-abf9e46b920f)


### Planning Stage

#### Target Audiences:

•	Recruiters in the painting and decorating profession.

•	Individuals looking for a painter and decorator

#### User Stories:

•	As a user, I want to view some of the work the candidate has done.

•	As a user, I want to learn about the candidate’s knowledge and skills.

•	As a user, I want to navigate the page to find what I require quickly and easily.

•	As a user, I want to reach out and contact the candidate.

•	As a user, I want to know how to contact the candidate.

•	As a user, I want to find more about the candidate on social media.

•	As a user, I want to be able to easily navigate throughout the site to find content.

#### Site Aims:

•	To provide an opportunity for the user to get to know my skills and knowledge.

•	To offer the user various options of getting in contact.

•	To provide the user the opportunity to download my CV.

•	To provide a contact form the user can complete if they would rather not phone, email or contact via social media.

### Design


#### Typography

•	Throughout the page, the following fonts are used: font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif.

#### Wireframes:

Wireframes for desktop, tablet and mobile phone devices were created using Balsamiq. This process provides a basic but clear outline of how the website would look on each device.

![Desktop wireframe Project 1](https://github.com/user-attachments/assets/fcac4969-902d-4400-bbac-a43214746f99)


![Tablet wireframe Project 1](https://github.com/user-attachments/assets/8d0ab388-673d-4823-8b3d-78f964eb650a)


![Mobile Phone wireframe Project 1](https://github.com/user-attachments/assets/faded3b1-e85f-480f-9aa2-a2f8e3ac4c52)


### Features

#### •	Responsive on all device sizes

#### •	Interactive elements for user e.g. contact form

#### •	Navigation Bar

o	The name is present on the left side of the header together with phone number and email address and the navigation links are aligned to the right.

o	The user is given links to the home, about, portfolio and contact pages.

o	Each navigation link features a hover effect too provide visual feedback to the user.

o	Each page features an active link to provide instant feedback to the user as to their location on the site.

o	The header is fully responsive and uniform across all three pages of the site.

o	On smaller screens a hamburger menu is provided to ensure mobile users have an optimal experience.

### Testing Phase

#### Responsiveness

•	Responsiveness was tested extensively using Chrome Dev Tools. This proved invaluable when creating each page and was instrumental in helping me ensure responsiveness on multiple devices and screen sizes. 

•	User testing was conducted on the following devices on various mobile (both android and iphone), desktop (windows desktop) and tablet (Samsung galaxy) devices. In each case, the pages responded as expected.

#### Functionality

•	Each feature was user-tested numerous times. All links were clicked and images checked.

•	The header is responsive and each of the links and hamburger menu function as desired.

•	The javascript behaves as expected regardless of the device.

•	The social media links within the footer all work as expected on all pages, taking the user to the relevant link in a new tab.

•	The download cv button works

•	The phone and email links work

•	The contact link within the cover-text takes the user to the contact page when clicked.

•	On the contact page the form inputs and validation work as expected.

•	I used Lighthouse to test website. Results below:

![image](https://github.com/user-attachments/assets/2d5b02ad-c685-4365-bbcb-ba12348a29e8)

Validators
•	HTML Validation using w3c validator 

![image](https://github.com/user-attachments/assets/024bdbfa-5cc3-4719-b237-524c5368b269)

CSS Validation using w3c jigsaw

![image](https://github.com/user-attachments/assets/1c4b9a5e-50c8-48cb-9052-dfc2831d053d)

### Deployment

I deployed the page on GitHub pages via the following procedure: -

1.	From the project's repository, go to the Settings tab.
2.	From the left-hand menu, select the Pages tab.
3.	Under the Source section, select the Main branch from the drop-down menu and click Save.
4.	A message will be displayed to indicate a successful deployment to GitHub pages and provide the live link.The live site can be found can be found at the following URL - https://dito-gee.github.io/Resume/

### Tech

I used the following technologies for the project:

•	HTML

•	CSS

•	JavaScript

### Software
The following software was used:

•	Gitpod to create, load and push my code to Github.

•	Git (Gitpod and Github) as my version control for the site.

•	Balsamiq wireframes software.

### Credits

#### Content:

##### The bootstrap JS javascript code (below) was taken from bootstrap 5 - CDN via jsDelivr.
<script src=https://cdn.jsdelivr.net/npm/bootstrap@5.3.6/dist/js/bootstrap.bundle.min.js integrity="sha384j1CDi7MgGQ12Z7Qab0qlWQ/Qqz24Gc6BM0thvEMVjHnfYGF0rmFCozFSxQBxwHKO"crossorigin="anonymous"></script>
t>

##### The Bootstrap CSS link javascript code (below) was taken from bootstrap 5 - CDN via jsDelivr.
<link href=https://cdn.jsdelivr.net/npm/bootstrap@5.3.6/dist/css/bootstrap.min.css rel="stylesheet” integrity="sha3844Q6Gf2aSP4eDXB8Miphtr37CMZZQ5oXLH2yaXMJ2w8e2ZtHTl7GptT4jmndRuHDT" crossorigin="anonymous">


##### The Lightbox enhancement for better "view project" functionality javascript code (below) was taken from Lightbox2 Library version 2.11.3 - cdnjs.cloudflare.com.


<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.11.3/css/lightbox.min.css">

<script src="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.11.3/js/lightbox.min.js"></script>
<script>
lightbox.option({
'resizeDuration': 200,
'wrapAround': true
})
</script>


##### The javascript code (below) was taken from WebKit Bug #10660 (Oct 2006)

<script>
//  Update copyright year automatically
document.getElementById('year').textContent = new Date().getFullYear();

The javascript code (below) was taken from CSS-Tricks (2018).


// Smooth scrolling for navigation links
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
anchor.addEventListener('click', function (e) {
e.preventDefault();
document.querySelector(this.getAttribute('href')).scrollIntoView({
behavior: 'smooth'
});
});
});

The javascript code (below) was taken from Stack Overflow (2020–2021).


// Close mobile menu when clicking a nav link
const navLinks = document.querySelectorAll('.nav-link');
const navbarCollapse = document.querySelector('.navbar-collapse');

navLinks.forEach(link => {
link.addEventListener('click', () => {
if (navbarCollapse.classList.contains('show')) {
const bsCollapse = new bootstrap.Collapse(navbarCollapse);
bsCollapse.hide();
}
});
o	});
</script>


##### The  navigation section code (below) was derived with the help of Bootstrap 5 Navbar Docs.

    
    <nav class="navbar navbar-expand-lg navbar-dark sticky-top">
        <div class="container">
            <a class="navbar-brand me-5" href="index.html">Nderitu Githaiga</a>
            <!-- Phone number -->
            <p class="contact-item" style="margin-right: 20px;">
                <i class="fas fa-phone contact-icon"></i>
                <a href="tel:+447851349247 ">+44 7851349247</a>
            </p>
            <!-- Email address -->
            <p>
                <i class="fas fa-envelope contact-icon "></i>
                <a href="mailto:nderitug@yahoo.com">nderitug@yahoo.com</a>
            </p>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link active" href="#home">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#portfolio">Portfolio</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

Social media, phone and email icons were taken from https://fontawesome.com/

The contact form is loosely based on Code Insitute's Love Running walkthrough project.

### Media:

•	The profile image is of myself taken by me.

•	All the images used are my own personal images taken at work.

### Honorable mentions

Thank you to my mentor, Richard Wells, who gave a significant amount of his time to provide me with feedback and ideas on the project.



















 



