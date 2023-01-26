const enhance = id => {
    const element = document.getElementById(id),
        text = element.innerText.split("");
        /* console.log(text) */
        element.innerText = "";

        text.forEach(letter => {
            const span = document.createElement("span");

            span.className = "letter";

            span.innerText = letter;

            element.appendChild(span);
        });
        }

        enhance("Fileserver")
        enhance("RUB-Motorsport")
        enhance("YouTube")
        enhance("Wiki")
        enhance("PDM")

        
        
        
        var xhr = new XMLHttpRequest();
        xhr.open("GET", "https://cgi.nidaku.de/cgi-bin/workshop.cgi");
        xhr.send();
        xhr.onload = function () {
          var js = JSON.parse(xhr.response);
          console.log(js.lightOn);
          //var dcm = document.getElementById("shopstate");
          if (js.lightOn) {
            //dcm.style.color = "#ffffff";
            //dcm.innerHTML = "OPEN"; 
            document.getElementById("open-lock").style.display = "block";
            document.getElementById("closed-lock").style.display = "none";
            //document.getElementById("openG").style["background-color"] = "#2CD487" ;
            
    
          } else {
            //dcm.style.color = "#ffffff";
            //dcm.innerHTML = "CLOSED";
            document.getElementById("open-lock").style.display = "none";
            document.getElementById("closed-lock").style.display = "block";
            //document.getElementById("openG").style["background-color"] = "#F15352" ;
          }
        };
      
      
        xhr.onerror = function () {
          alert(`There was an error fetching the current state`);
        };
      
        
        var acc = document.getElementsByClassName("accordion");
                  var i;
      
                  for (i = 0; i < acc.length; i++) {
                    acc[i].addEventListener("click", function () {
                      this.classList.toggle("active");
                      var panel = this.nextElementSibling;
                      if (panel.style.display === "block") {
                        panel.style.display = "none";
                      } else {
                        panel.style.display = "block";
                      }
                    });
                  }
      
        
