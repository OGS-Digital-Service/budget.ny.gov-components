---
layout: dob.njk
title: Employment at DOB
---
{% from './_includes/_components.njk' import hero,categorytiles,card,bio,textarea,highlight,iconframe  %}
                   
{{ hero({ 
    title:"Employment at DOB",
    date: "February 16, 2022",
    image:"ilovenycapitol.jpg",
    description:"The Divison of the Budget is a vibrant, challenging, and creative place to work. Come be part of the team that keeps Government moving forward.",
    buttons: [
        {
            text:"Open Positions",
            link:"https://statejobs.ny.gov/public/vacancyTable.cfm?searchResults=Yes&Keywords=&title=&JurisClassID=&AgID=3&minDate=&maxDate=&employmentType=&grade=&SalMin=",
            arialabel:"Go to state jobs to see our open jobs"
        },
        {
            text:"Become a Budget Specialist",
            link:"#",
            arialabel:""
        }
    ]

})}}

{{  highlight({
    title: "Who We Are",
    content:"An awesome and impactful statement about who we are as an agency! Think about something really engaging that demonstrates the values of the agency and the imapct of the work.",
    link:"https://budget.ny.gov",
    linktext:"This link is optional",
    framecolor:"gray"
})}}

<section class="nysds-textarea my-14 w-11/12 max-w-7xl flex flex-col justify-center m-auto">
<!-- frame heading -->
<h2 class="nysds-text-36 font-extrabold text-center mb-4 w-full text-black">What we do</h2>
<p> A placeholder for a paragraph of text! </p>
<section class="flex flex-col justify-center text-center my-8">
<h3 class="nysds-text-32 font-bold text-admin-first my-4"> Image Placeholder</h3>
<img loading="lazy" class="m-auto w-full md:w-2/3 lg:w-1/2" src="/img/plaza-lights2.jpg" alt="put some descriptive alt text here" />
<p class="my-2 italic"> The Plaza lit up with fancy new lights </p>
</section>
<p> A placeholder for another paragraph of text! </p>
</section>

{{ iconframe({
    title:"An Icon Frame",
    color:"",
    iconcards: [
        {
            icon:"nygov-logo.png",
            iconalt:"an outline of the state of new york",
            title: "Icon Title",
            content:"One really good decriptive sentence that shouldn't be terribly long. "
        },
        {
            icon:"nygov-logo.png",
            iconalt:"an outline of the state of new york",
            title: "Icon Title",
            content:"One really good decriptive sentence that shouldn't be terribly long. "
        },
        {
            icon:"nygov-logo.png",
            iconalt:"an outline of the state of new york",
            title: "Icon Title",
            content:"One really good decriptive sentence that shouldn't be terribly long. "
        },
        {
            icon:"nygov-logo.png",
            iconalt:"an outline of the state of new york",
            title: "Icon Title",
            content:"One really good decriptive sentence that shouldn't be terribly long. "
        }

    ]
})
}}


{{  highlight({
    title: "How We Hire",
    content:"How we hire placeholder text",
    link:"https://budget.ny.gov",
    linktext:"This doesn't have to be here",
    framecolor:"orange"
})}}





{{ card({ 
    frametitle:"Discover Your Next Career Opportunity",
    cards: [
        {
           title:"Current Openings",
           content:"A sentence or two of text that gives the general idea of what this link goes to or the topic of the page.",
           link:"https://budget.ny.gov",
           arialabel:"",
           image:"/img/Business_Masks2.jpg",
           imagealt:"Office workers in a conference room having a collaborative working session"
        },
        {
           title:"Internships",
           content:"A sentence or two of text that gives the general idea of what this link goes to or the topic of the page.",
           link:"https://budget.ny.gov",
           arialabel:"",
           image:"/img/plaza-lights2.jpg",
           imagealt:"Office workers in a conference room having a collaborative working session"
        },
        {
           title:"Apply Now",
           content:"A sentence or two of text that gives the general idea of what this link goes to or the topic of the page.",
           link:"https://budget.ny.gov",
           arialabel:"",
           image:"/img/Business_Masks2.jpg",
           imagealt:"Office workers in a conference room having a collaborative working session"
        }
    ]
})}}


{{  highlight({
    title: "DOB is an Equal Opportunity Employer",
    content:"EEO Statement Placeholder",
    link:"https://budget.ny.gov",
    linktext:"Read our Equal Employment Opportunity Statement",
    framecolor:"orange"
})}}

{{ bio({
    title:"What is it like to work for DOB?",
    content:"Working for Budget is like winning the superbowl and getting knighted at the same time. I feel amazing everyday!",
    image:"/img/Business_Masks2.jpg",
    imagealt:"office workers collaborating in a conference room"
})}}


{{ categorytiles({ 
    title:"Learn More",
    items: [
        {
            text:"The Empire State Plaza",
            link:"https://empirestateplaza.ny.gov"
        },
        {
            text:"Budget Specialists",
            link:"https://budget.ny.gov"
        },
        {
            text:"Working for NYS",
            link:"https://budget.ny.gov"
        },
        {
            text:"Albany!",
            link:"https://www.albany.org/"
        }
    ]
})}}
