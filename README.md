# Web Development Assignment one

This assignment involves the creation of HTML pages with specified structure and functionality. The task is divided into three main parts:

1. **Structure the folder of your website on CSHost**  
2. **Create your home page**  
3. **Create a Community of Practice website**

## Requirements

### 1. Structure the Website Folder

You need to structure your web folder on CSHost by following these steps:

- Log into the hosting server and open the `public_html` directory.
- Upload your home page file to the `public_html` folder.
- Create three new folders within the `public_html` directory:
  - `ass`
  - `examples`
  - `project`
  
- Inside each of these folders, create a new `index.html` file, which will be the default web page displayed when visitors browse to the folder.

- Within each of the three main folders, create a subfolder with a number assigned (e.g., `ass1`, `examples1`, etc.), and inside each subfolder, create a new `index.html`.

- Inside the `examples` folder, create another subfolder called `htmlEx`. Upload the HTML examples discussed in the lecture, and make an `index.html` file to refer to these examples.

### 2. Create Your Home Page

Your home page should include:
- A biography section with personal information (name, student ID, department).
- An education section detailing your school and university education, graduation dates, and links.
- A training section that lists any courses you have completed.
- Employment and internship information.
- A section for community and voluntary work.
- Awards and distinctions.
- Your study timetable for the semester.

### 3. Community of Practice Website

For the **Community of Practice** website, you must:
- Create a home page for your community with a unique name, objectives, logo, and navigation to the four functionalities.
- Include the following features:
  - User profiles
  - Knowledge base
  - Article creation
  - File sharing
  - Search functionality
  
#### Steps to Implement:
- **Create static HTML pages** for the features mentioned above.
- **Use HTML5 form validation attributes** for any form elements to ensure data accuracy.
- Implement **accessibility features** like descriptive labels and keyboard accessibility.
- All forms should use the `POST` method to submit data to the provided URL (`http://yhassouneh.studentprojects.ritaj.ps/util/process.php`).

### General Requirements

- **Header**: Contains logo, site title, and navigation links.
- **Main Section**: Contains page-specific content.
- **Footer**: Contains community contact information (address, telephone number, email), and copyright.
- Use **relative links** for all internal links within the site.
- **W3C Validation**: Ensure all pages pass validation using the W3C HTML validator (http://validator.w3.org/).
- All forms must submit data via the `POST` method to the provided URL.
- Your home page and community website should be accessible through `http://web{STUDENT_ID}.studentswebprojects.ritaj.ps/`.

## Files Structure

```plaintext
public_html/
├── index.html
├── ass/
│   ├── ass1/
│   │   └── index.html
│   └── index.html
├── examples/
│   ├── htmlEx/
│   │   └── index.html
│   └── index.html
└── project/
    ├── project1/
    │   └── index.html
    └── index.html
