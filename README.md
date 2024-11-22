<img src="images/headerrm.png">

<br><br>

# <i><b>About This Project</b></i>
Hello everyone, my name is <b><i>Muhammad Rifqi Saleh</i></b> ! <br/> <br/>
As part of my software engineering course, i was tasked to make a simple website based of HTML and design it with CSS. This website consist of sticky Navbar, log in & enquiry form, Introduction paragraph and gallery preview. This projects presents a simple company profile of a flying club in Jakarta. The focus of this website is to provide basic explanation and introduction of the company.

Visit this link (https://aeroindahflyingclub.site/) to access my deployment !



[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/rifqisaleh) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muhammad-rifqi-saleh-77b61911a/) 

<br/>


## <i><b> Table of Contents </b></i>
<ul><li>Technologies Used</li>
<li>Structures</li>
<li>Setup</li>
<li>Deployment</li></ul>


<br/>

## <i><b> Technologies used </b></i>

`HTML 5` `CSS`

<br/>

## <i><b> Structures </b></i> <br/>

The structures of the html site consist of:

**1.** Header
- Navbar
- Company Short Intro

<br>

**2.** Main
- Our Mission Section
- Available Programs Section
- Available Fleet Section
- Team Section
- Enquiries Section

<br>

**3.** Footer
- Additional Navigation Bar


## <i><b>Setup</b></i> <br/>

1. Through your preferred terminal, clone the repository:<br>
    [`https://github.com/rifqisaleh/milestone1-rifqisaleh-.git`]

2. Navigate to the project directory:<br>
    `cd milestone1-rifqisaleh`

3. Open the `index.html` file in your browser:
   
4. For accessing any pictures from "images" folder, you can use: <br>
    `<img src="../images/headerplane.jpg"`

5. Create a new branch under the name  "develop/(your name)" and switch to your new branch<br>
    
    `git branch -b "develop/(yourname)"`

    `git checkout -b "develop/(yourname)"`

6. Modify or customise as needed and push the file if you are done<br>

    `git add.`

    `git commit -m"update message" / Put a short and concise message`

    `git push origin develop/(yourname)`

7. Merge into main branch <br>
    
    `git checkout main`

    `git pull origin main / pull latest version before merging`

    `git merge develop/(yourname)/ Please resolve any conflicts`

    `git push origin main`


<br>

## <i><b> Deployment </b></i> <br>
In this section, i will explain my website deployment process. This sections are divided into 5 sections. Which includes:
1. Website/Tools Used
2. Deployment
3. Domain Registration
4. Auto Deployment

<br>
<li><b>Website/Tools Used</b><br>
The tools/website that are used for this deployment are:
<ul>

[My Github Repo](https://github.com/rifqisaleh/milestone1-rifqisaleh-.git)<br>
[Netifly](https://www.netlify.com/) <br>
[Niagahoster](https://www.niagahoster.co.id/)

</ul>


<br>
<li><b>Deployment</b><br>
<br>

- After signing in, i proceed to import my existing repository by clicking the "Import From Git" on my main netifly page.

- It will then lead to a page where i can choose to export my project from different git provider. In this case, i'll be using Repo from github. It will prompt to select a specific repo to deploy. 
<br/> <img src="images/deployment2.png">

- I chose "aeroindahflyingclub" as my site name. It will then check my preferred name availability. Within the same page, i then proceeds to deploy my project by clicking `Deploy aeroindahflyingclub`.
<br/> <img src="images/deployment3.png">

- It will then revert back to site overview, where i can observe the deployment progress. When the deployment are done, a success message popped up. 
<br/>

<li><b>Domain Registration</b></li><br/>

- For this deployment, i will be using a local domain hosting, niagahoster.

- After log-in, i clicked `Miliki Domain Baru`, add my preferred site name and then purchase the preferred domain. Next, i set the site configuration and personal contact information. <br/> <img src="images/hosting1.png">

- If successful,the page then redirected to `Ringkasan Domain`, and then i need to configure the DNS name. <br/> <img src="images/hosting3.png">

- To set up the DNS name, i went back to netifly and on the Site Overview page, i chose `Set Up a Custom Domain`. I then add and verify my preferred site name (aeroindahflyingclub.site). Afterwards, i proceeds to `Add Domain`.

- The page then redirected to Domain Management, and just to the right of "aeroindahflyingclub.site", i click `option` and `Go To DNS Panel`. <br/> <img src="images/hosting6.png">

- I then copy the four domain's name server, and paste it on niagahoster name server. After saving the DNS name, I waited at least 30 minutes before i can finally access my website.

<li><b>Auto Deplyment</b></li><br/>
Netifly enables auto deploymeny automatically after linking your repository. Any changes that were pushed to the repo will automatically revise the deployed website.