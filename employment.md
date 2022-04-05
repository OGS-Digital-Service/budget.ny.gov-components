---
layout: dob.njk
title: Employment at DOB
url: budget.ny.gov/employment
domain: budget.ny.gov
facebook:
    title:  Employment at DOB
    description: Supporting all areas of public policy, work at the Division of the Budget is high-impact public service
    image: ilovenycapitol.jpg
twitter:
    title: Employment at DOB
    description: Supporting all areas of public policy, work at the Division of the Budget is high-impact public service
    image: ilovenycapitol.jpg
---
---
{% from './_includes/_components.njk' import hero,categorytiles,card,bio,textarea,highlight,iconframe,quicklinks  %}
                   
{{ hero({ 
    title:"Careers at DOB",
    date: "February 16, 2022",
    image:"ilovenycapitol.jpg",
    description:"Supporting all areas of public policy, work at the Division of the Budget is high-impact public service.",
    buttons: [
        {
            text:"View Openings",
            link:"https://statejobs.ny.gov/public/vacancyTable.cfm?searchResults=Yes&Keywords=&title=&JurisClassID=&AgID=3&minDate=&maxDate=&employmentType=&grade=&SalMin=",
            arialabel:"Go to state jobs to see our open jobs"
        },
        {
            text:"Apply Now",
            link:"#",
            arialabel:""
        }
    ]

})}}

<section class="nysds-textarea my-14 w-11/12 max-w-7xl flex flex-col justify-center m-auto">
<!-- frame heading -->
<h2 class="nysds-text-36 font-extrabold text-center mb-4 w-full text-black">Who We Are</h2>
<p>The New York State Division of the Budget (DOB) is the primary fiscal advisor to the Governor, developing, negotiating and implementing one of the largest government budgets in the nation. Our staff work on the forefront of emerging issues and challenges, developing and managing the “nuts & bolts” of the services and policies that impact the daily lives of New Yorkers. If you are looking for a place to start your career in government finance or public policy, are interested in collaborating and learning from talented and dedicated analysts or are excited about the challenge of addressing the continually evolving issues that face State government, apply to join our team!</p>
</section>

{{ iconframe({
    title:"What We Do",
    color:"",
    description:"Our work impacts all areas of public policy and provides opportunities for employees to develop in-depth policy knowledge and make meaningful contributions as they engage in:",
    iconcards: [
        {
            icon:"nygov-logo.png",
            iconalt:"an outline of the state of new york",
            title: "Skilled Policy and Program Analysis",
            content:"Analyzing government programs, operations, and legislative proposals for fiscal implications."
        },
        {
            icon:"nygov-logo.png",
            iconalt:"an outline of the state of new york",
            title: "Complex Budget Coordination",
            content:"Creating, proposing and negotiating budget and policy, while managing the
State’s multi-year financial plan."
        },
        {
            icon:"nygov-logo.png",
            iconalt:"an outline of the state of new york",
            title: "Revenue and Economic Forecasting",
            content:"Interpreting fiscal trends and impacts to promote long-term financial stability."
        },
        {
            icon:"nygov-logo.png",
            iconalt:"an outline of the state of new york",
            title: "High Performance Government Management",
            content:"Providing enterprise guidance, overseeing government performance, and managing initiatives.  "
        }

    ]
})
}}






{{ card({ 
    frametitle:"Discover Your Next Career Opportunity",
    cards: [
        {
           title:"Current Openings",
           content:"DOB employs budget and policy analysts, auditors, economists, contract specialists, human resources and administrative professionals, student interns, and more.",
           link:"https://budget.ny.gov",
           arialabel:"",
           image:"/img/Meeting.jpg",
           imagealt:"Office workers in a conference room having a collaborative working session"
        },
        {
           title:"Internships",
           content:"Gain valuable experience in public policy and government finance through an internship at DOB.",
           link:"https://budget.ny.gov",
           arialabel:"",
           image:"/img/Laptop.jpg",
           imagealt:"Office workers in a conference room having a collaborative working session"
        },
        {
           title:"Submit an Application",
           content:"Are you ready for your next great career opportunity? Submit an application today!",
           link:"https://budget.ny.gov",
           arialabel:"",
           image:"/img/Handshake.jpg",
           imagealt:"Office workers in a conference room having a collaborative working session"
        }
    ]
})}}


<section class="nysds-textarea my-14 w-11/12 max-w-7xl flex flex-col justify-center m-auto">
<!-- frame heading -->
<h2 class="nysds-text-36 font-extrabold text-center mb-4 w-full text-black">Our Workplace is for Everyone</h2>
<p>DOB is an Equal Employment Opportunity employer. Candidates with diverse backgrounds, veterans, and people with disabilities are encouraged to apply. State law prohibits discrimination based on race, color, creed, sex, national origin, age, mental or physical disability, marital status, military or veteran status, sexual orientation, predisposing genetic characteristics, gender identity, domestic violence victim status, and prior arrest, youthful offender adjudications, sealed records, and/or previous conviction records.</p>
<a class="nysds-exclude uppercase bg-admin-first visited:!text-white m-auto !no-underline hover:bg-black hover:!underline focus:bg-black focus:!underline my-4 p-4 rounded-xl !text-white text-center w-2/3 md:w-1/3 lg:w-1/4" href="https://budget.ny.gov">Read our Equal Employment Opportunity Statement</a>  
</section>


{{ bio({
    title:"What is it like to work for DOB?",
    content:'"There are many intelligent Examiners here, but no will do the job just like you. Your unique and diverse input matters. Every possible policy area you can think of, every possible skill… there’s really a role for everybody. "',
    attribute:"Jacob, Budget Examiner",
    image:"/img/bio-image.jpg",
    imagealt:"professional headshot of male employee wearing a suit"
})}}


{{ quicklinks({ 
    frametitle:"Learn More",
    colleft: [
        {
            title:"Salaries and Benefits",
            link:"https://budget.ny.gov",
            content:"",
            image:"/img/benefits-card.jpg"
        },
        {
            title:"Life in the Capital Region",
            link:"https://budget.ny.gov",
            content:"",
            image:"/img/life-card.jpg"
        }
    ],
    colright: [
        {
            title:"Career Paths",
            link:"https://budget.ny.gov",
            content:"",
            image:"/img/career-card.jpg"
        },
        {
            title:"Learning and Leadership Development",
            link:"https://budget.ny.gov",
            content:"",
            image:"/img/learn-card.jpg"
        }
    ]
})}}