// Create a LinkedIn profile object
const linkedInProfile = {
    name: "Aliza Ali",
    intro : "Experianced Full Stack Develloper\tMobile App & Website Developer\tTurning Idea Into Seamless Digital Experiance",
    com_uni : "Mercury Sols\tThe Islamia University of Bwp" ,
    followers : "3,294 followers\t500+ connections",
    github : "https://github.com/stackmasteraliza",
    about : "I'm a Full Stack Developer passionate about building user-centric websites and hybrid apps" ,
    top_skill : "Larvel\tReact Native\tFlutter\tWeb Application Development\tJava Script",
    
    experiance : {
        experiance_1:{
        company:"Mercury Sols",
        position : "Full Stack Developer",
        year : "June 2023 - Present ",
        job_type: "On-Site",
        location:"Rahim Yar Khan Dis, Punjab , Pakistan ",
        skill: ["Andriod Developer " , "Flutter , Java Script React Native"],
        },
        experiance_2:{
        company:"Devfinix",
        position : "Full Stack Developer",
        year : "Nov 2022 - Present ",
        location:"Rahim Yar Khan Dis, Punjab , Pakistan ",
        job_type:"Remote",
        skill: ["Andriod Developer " , "Flutter , Java Script React Native"],
        },
        experiance_3:{
            company:"IT-Center",
            position : "Full Stack Developer",
            year : "Aug 2022 - Jun 2023 ",
            location:"Rahim Yar Khan Dis, Punjab , Pakistan ",
            job_type:"Intership",
            skill: "Flutter\tJava Script\tReact Native\tSQL\tWebDesign",
            },
    },
    

    education: {
        university: {
            institution: "The Islamia University Of Bwp",
            degree: "Bachelor of Science in Software Engirneerning",
            year: "2020-2023",
            grade: "3.97/4.00 CGPA"
        },
        intermediate: {
            college: "Nice Degree College",
            degree:"Pre-Engirneering",
            year: "Aug 2018- Sep 2020",
            grade: "1023/1100"
        },
       
    },
    certification: {
        certificate1:{
            institute_name:"Mercury Sols",
            cer_name:"Mobile Application Development ",
            cert_type:"Intership",
            issued_Date:"Sep 2023",
            skill:"Mobile Application\tFlutter",
        },
        certificate2:{
            institute_name:"NAVTTC",
            cer_name:"Web Design and Development ",
            cert_type:"Student",
            issued_Date:"Jul 2023",
            skill:"Web DEvelopment \tWeb Design",
        },
        certificate3:{
            institute_name:"IT-Center ",
            cer_name:"Full Stack  and WEb Development ",
            cert_type:"Student",
            issued_Date:"Oct 2022",
            skill:"Laravel\tBootstrap\tjQuery\tHTML5\tCSS3\tJAvaScript",
        }

    },
    project:{
        project_1:{
            project_name:"Code Blendr",
            time_period:"Apr 2024-May 2024",
            assositation:"The University of Bwp",
            descrip:"Converet the code one to another",
            skill:"Laravel\tCodellama",
        },
        project_2:{
            project_name:"P2P Chat",
            time_period:"Jun 2023 - July 2023",
            assositation:"Mercury Sols",
            descrip:"P2P chat is sleek chatiing app",
            skill:"Flutter\tFirebase",
        },    

    },
    Languages:{
        Languages_1 :{
            namae : "English",
            proficiency : "Full Proffessional Proficiency"
        },
        Languages_2 :{
            namae : "Urdu",
            proficiency : "Native or Bilingual Proficiency"
        }

    },
    profession: "Professional Developer"
};

// Print the LinkedIn profile object using console.log
console.log("LinkedIn Profile:");
console.log("Name:", linkedInProfile.name);
console.log("Intro:");
console.log("  -", linkedInProfile.intro);
console.log("Companies/Universities:", linkedInProfile.com_uni);
console.log("Followers:", linkedInProfile.followers);
console.log("GitHub:", linkedInProfile.github);
console.log("About:", linkedInProfile.about);
console.log("Top Skills:");
console.log("  -", linkedInProfile.top_skill);
console.log("Experience:");
console.log("  Experience 1:");
console.log("    Company:", linkedInProfile.experiance.experiance_1.company);
console.log("    Position:", linkedInProfile.experiance.experiance_1.position);
console.log("    Year:", linkedInProfile.experiance.experiance_1.year);
console.log("    Job Type:", linkedInProfile.experiance.experiance_1.job_type);
console.log("    Location:", linkedInProfile.experiance.experiance_1.location);
console.log("    Skills:");
console.log("      -", linkedInProfile.experiance.experiance_1.skill[0]);
console.log("      -", linkedInProfile.experiance.experiance_1.skill[1]);

console.log("  Experience 2:");
console.log("    Company:", linkedInProfile.experiance.experiance_2.company);
console.log("    Position:", linkedInProfile.experiance.experiance_2.position);
console.log("    Year:", linkedInProfile.experiance.experiance_2.year);
console.log("    Job Type:", linkedInProfile.experiance.experiance_2.job_type);
console.log("    Location:", linkedInProfile.experiance.experiance_2.location);
console.log("    Skills:");
console.log("      -", linkedInProfile.experiance.experiance_2.skill[0]);
console.log("      -", linkedInProfile.experiance.experiance_2.skill[1]);

console.log("  Experience 3:");
console.log("    Company:", linkedInProfile.experiance.experiance_3.company);
console.log("    Position:", linkedInProfile.experiance.experiance_3.position);
console.log("    Year:", linkedInProfile.experiance.experiance_3.year);
console.log("    Job Type:", linkedInProfile.experiance.experiance_3.job_type);
console.log("    Location:", linkedInProfile.experiance.experiance_3.location);
console.log("    Skills:", linkedInProfile.experiance.experiance_3.skill);

console.log("Education:");
console.log("  University:");
console.log("    Institution:", linkedInProfile.education.university.institution);
console.log("    Degree:", linkedInProfile.education.university.degree);
console.log("    Year:", linkedInProfile.education.university.year);
console.log("    Grade:", linkedInProfile.education.university.grade);
console.log("  Intermediate:");
console.log("    College:", linkedInProfile.education.intermediate.college);
console.log("    Degree:", linkedInProfile.education.intermediate.degree);
console.log("    Year:", linkedInProfile.education.intermediate.year);
console.log("    Grade:", linkedInProfile.education.intermediate.grade);

console.log("Certifications:");
console.log("  Certificate 1:");
console.log("    Institute:", linkedInProfile.certification.certificate1.institute_name);
console.log("    Certificate Name:", linkedInProfile.certification.certificate1.cer_name);
console.log("    Type:", linkedInProfile.certification.certificate1.cert_type);
console.log("    Issued Date:", linkedInProfile.certification.certificate1.issued_Date);
console.log("    Skills:", linkedInProfile.certification.certificate1.skill);

console.log("  Certificate 2:");
console.log("    Institute:", linkedInProfile.certification.certificate2.institute_name);
console.log("    Certificate Name:", linkedInProfile.certification.certificate2.cer_name);
console.log("    Type:", linkedInProfile.certification.certificate2.cert_type);
console.log("    Issued Date:", linkedInProfile.certification.certificate2.issued_Date);
console.log("    Skills:", linkedInProfile.certification.certificate2.skill);

console.log("  Certificate 3:");
console.log("    Institute:", linkedInProfile.certification.certificate3.institute_name);
console.log("    Certificate Name:", linkedInProfile.certification.certificate3.cer_name);
console.log("    Type:", linkedInProfile.certification.certificate3.cert_type);
console.log("    Issued Date:", linkedInProfile.certification.certificate3.issued_Date);
console.log("    Skills:", linkedInProfile.certification.certificate3.skill);

console.log("Projects:");
console.log("  Project 1:");
console.log("    Project Name:", linkedInProfile.project.project_1.project_name);
console.log("    Time Period:", linkedInProfile.project.project_1.time_period);
console.log("    Association:", linkedInProfile.project.project_1.assositation);
console.log("    Description:", linkedInProfile.project.project_1.descrip);
console.log("    Skills:", linkedInProfile.project.project_1.skill);

console.log("  Project 2:");
console.log("    Project Name:", linkedInProfile.project.project_2.project_name);
console.log("    Time Period:", linkedInProfile.project.project_2.time_period);
console.log("    Association:", linkedInProfile.project.project_2.assositation);
console.log("    Description:", linkedInProfile.project.project_2.descrip);
console.log("    Skills:", linkedInProfile.project.project_2.skill);

console.log("Languages:");
console.log("  Language 1:");
console.log("    Name:", linkedInProfile.Languages.Languages_1.namae);
console.log("    Proficiency:", linkedInProfile.Languages.Languages_1.proficiency);
console.log("  Language 2:");
console.log("    Name:", linkedInProfile.Languages.Languages_2.namae);
console.log("    Proficiency:", linkedInProfile.Languages.Languages_2.proficiency);

console.log("Profession:", linkedInProfile.profession);
