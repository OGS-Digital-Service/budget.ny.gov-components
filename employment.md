---
layout: dob.njk
title: Employment at DOB
---
{% from './_includes/_components.njk' import hero,categorytiles,card,bio,textarea,highlight,iconframe  %}
                   
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
<p> The New York State Division of the Budget (DOB) is the primary fiscal advisor to the Governor, developing, negotiating and implementing one of the largest government budgets in the nation. Our work impacts all areas of public policy, from education to transportation and energy to health.</p>
<p>
If you’re looking for a place to start your career in government finance or public policy, or are looking for a role where you can realize your potential, apply to join our team!
</p>
</section>

{{ iconframe({
    title:"What We Do",
    color:"",
    description:"DOB serves on the front lines of emerging issues and challenges, developing and managing the “nuts & bolts” of the services and policies that impact the daily lives of New Yorkers, including:",
    iconcards: [
        {
            icon:"nygov-logo.png",
            iconalt:"an outline of the state of new york",
            title: "Skilled Policy and Program Analysis",
            content:"Analyzing the efficiency and effectiveness of programs and operations and proposed legislation. "
        },
        {
            icon:"nygov-logo.png",
            iconalt:"an outline of the state of new york",
            title: "Complex Fiscal Management",
            content:"Developing budget and policy recommendations. "
        },
        {
            icon:"nygov-logo.png",
            iconalt:"an outline of the state of new york",
            title: "Revenue and Economic Forecasting",
            content:"Analyzing fiscal trends and impacts. "
        },
        {
            icon:"nygov-logo.png",
            iconalt:"an outline of the state of new york",
            title: "Intergovernmental Relations",
            content:"Interacting with local governments, state agencies, and negotiating with legislative staff. "
        }

    ]
})
}}


{{  highlight({
    title: "How We Hire",
    content:"At DOB, we’re always looking for great candidates to add to our team, with or without a civil service exam. Don’t see an opening for the role you’re looking for? Submit an application anyway, and we’ll reach out if there’s an opportunity we think would be a good fit for you!",
    link:"https://budget.ny.gov",
    linktext:"Submit your application",
    framecolor:"orange"
})}}





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


{{  highlight({
    title: "Our Workplace is for Everyone",
    content:"DOB is an Equal Employment Opportunity employer. Candidates with diverse backgrounds, veterans, and people with disabilities are encouraged to apply. State law prohibits discrimination based on race, color, creed, sex, national origin, age, mental or physical disability, marital status, military or veteran status, sexual orientation, predisposing genetic characteristics, gender identity, domestic violence victim status, and prior arrest, youthful offender adjudications, sealed records, and/or previous conviction records",
    link:"https://budget.ny.gov",
    linktext:"Read our Equal Employment Opportunity Statement",
    framecolor:"orange"
})}}

{{ bio({
    title:"What is it like to work for DOB?",
    content:'"There are many intelligent Examiners here, but no will do the job just like you. Your unique and diverse input matters. Every possible policy area you can think of, every possible skill… there’s really a role for everybody. "',
    attribute:"Jacob, Budget Examiner",
    image:"/img/bio-image.jpg",
    imagealt:"professional headshot of male employee wearing a suit"
})}}


{{ categorytiles({ 
    title:"Learn More About",
    items: [
        {
            text:"Salaries and Benefits",
            link:"#"
        },
        {
            text:"Life in the Capital Region",
            link:"#"
        },
        {
            text:"Career Paths",
            link:"#"
        },
        {
            text:"Learning and Leadership Development",
            link:"#"
        }
    ]
})}}
