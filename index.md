<script>
    function clickCounter() {
        if (typeof (Storage) !== "undefined") {
            if (localStorage.clickcount) {
                localStorage.clickcount = Number(localStorage.clickcount) + 1;
            } else {
                localStorage.clickcount = 1;
            }
            document.getElementById("result").innerHTML = localStorage.clickcount;
        } else {
            document.getElementById("result").innerHTML = "Sorry, your browser does not support web storage...";
        }
window.location = 'http://www.google.com';
    }
</script>

<button onclick="clickCounter();"><span style="font-size:35px;" font face="Face"> Please Click Here to Access QLM </span>
</button>


# My first page hosted on github pages

## Contact:
Computer Architecture and Microprocessor Engineering Lab [CAMEL](http://camel.clarkson.edu){:target="_blank"}  
CAMP-115  
Tel:+1-315-268-6538  
torresg at clarkson dot edu  

[CV](https://people.clarkson.edu/~torresg/vitae/Gildo_Torres_CV.pdf)   [Linkedin](https://www.linkedin.com/in/floating-point){:target="_blank"}  [ORCID](http://orcid.org/0000-0001-5758-4842){:target="_blank"}

Department of Electrical and Computer Engineering  
Wallace H. Coulter School of Engineering  
[Clarkson University](https://www.clarkson.edu){:target="_blank"}  
8 Clarkson Avenue  
Potsdam, NY 13699-5720  

## About:
The **About** section is still empty

## Publications: 
The **Publications** section is also still empty

## Education: 
**Clarkson University**, *Potsdam, New York*  
Doctor of Philosophy (Ph.D.), Electrical and Computer Engineering, 2012 - Present  
Advisor: Prof. Chen Liu  

**Florida International University**, *Miami, Florida*  
Master of Science (M.S.), Computer Engineering, 2011 - 2012  
Advisor: Prof. Chen Liu  

**Higher Polytechnic Institute at Havana**, *Havana, Cuba*  
Bachelor of Science (B.S.), Electrical Engineering, 2001 - 2006  
Advisor: Prof. Alejandro Cabrera Sarmientos  
V. I. Lenin, Havana, Cuba  
High School, Sciences, 1997 - 2000

