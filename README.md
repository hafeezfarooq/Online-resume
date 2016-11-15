# Online-resume
Udacity project
var bio = {
	"name": "Hafeez Farooq",
    "age":23,
	"role": "Web Developer",
	"contacts": {
		"mobile": "9746272920",
		"email": "hafeezknight93@gmail.com",
		"github": "hafeez",
		"location": "Trivandrum"
	},
	"welcome message": "Hey people!!",
	"skills": [
		"awesomness", "delivering things", "programming"
		]
};

var education = {
	"schools": [
	{
		"name": "BPM",
		"location": "Mangalapuram",
		"degree": "10th",
		"majors": "No particular majors",
		"dates": "6-7-2010",
		"url": "www.bpm.com"
	},
    {
		"name": "Sarvodaya",
		"location": "TVM",
		"degree": "12th",
		"majors": "no particular majors",
		"dates": "6-7-2012",
		"url": "www.sarvodaya.com"
	}
	],

	"onlineCourses": {
		"title": "Front-end engineer",
		"school": "Udacity",
		"dates": "1-9-2016",
		"url": "www.udacity.com"

	}
};

var work = {
	"jobs": { 
           "employer": "Qburst",
           "title": "System engineer", 
           "location": "Pattom", 
           "dates": "6-10-2016",
           "description": "Just a fake value" 
      /*display: function*/
    }
};

var projects = {
      "projects": { 
            "title": "Forcasting hereditary diseases", 
            "dates": "7-3-2016",
            "description": "Final year project",
            "images": "https://www.google.co.in/search?q=images+of+doctors&espv=2&biw=1396&bih=691&source=lnms&tbm=isch&sa=X&ved=0ahUKEwjL8tzsp6vQAhVHQo8KHRoLDKIQ_AUIBigB#tbm=isch&q=images+of+doctors+at+work&imgrc=L9s19YjDB22UgM%3A"
      /*display: function*/
    }
};
$("#main").append(bio.age);
$("#main").append(education.schools[0].name);
$("#main").append(work.jobs.employer);
$("#main").append(projects.projects.title);
