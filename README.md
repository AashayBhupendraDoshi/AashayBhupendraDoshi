<!--
### Hi there 👋


**AashayBhupendraDoshi/AashayBhupendraDoshi** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

```python

from datetime import datetime, timedelta

class Attributes(Aashay):
	@staticmethod
	def contact() -> tuple:
	    email    = "aashaydoshi97@gmail.com"
	    linkedin = "https://www.linkedin.com/in/abd77/"
	    
	    return email, linkedin
	
	@staticmethod
	def life() -> tuple:
	    langs         = ['English', 'Hindi']
	    nationality   = 'Indian'
	    dob_str = "17th July 1997"  # Given date of birth
	    dob = datetime.strptime(dob_str, "%dth %B %Y") 
	    age = (datetime.now() - dob)
	    
	    return langs, nationality, age
	
	@staticmethod
	def coding() -> tuple:
		langs 	      = ['python', 'go', 'typescript', 'java']
                databases     = ['PostgreSQL','MongoDB','ApacheKafka']
                frameworks    = ['Grpc/protocol-buffers', 'websockets', 
                                'FlasAPI', 'Pytorch', 'Pytorch-Geometric']
                specialities  = ['backend', 'distributed systems', 'AI/ML']
		environnement = ['vscode', 'nano']
		
		return langs, databases, frameworks, specialities, environnement

	@staticmethod
	def projects() -> tuple:
		return {
  			"Ask": {
     				"link": "https://chromewebstore.google.com/detail/ask/donmdonnblkneanplkifkejjlnhjjlhh/",
	 			"Descrition": "Chrome extension personalized AI assistant leveraging memory recall and context awareness"
			},
   			"RPi4b_cellular_OBDscanner": {
     				"link": "https://github.com/AashayBhupendraDoshi/RPi4b_cellular_OBDscanner",
	 			"Descrition": "OBD2 and Sensor Data Collection Agent for Raspberry Pi"
			},
   			"py_Face_Search": {
     				"link": "https://github.com/AashayBhupendraDoshi/py_Face_Search",
	 			"Descrition": "Python based GUI application for single and multi face search"
			},
   		
   			
		}

```
    
<h2 align="center">Skills </h2>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=aws,golang,java,ts,python,pytorch,fastapi,kafka,postgres,mongodb,docker,raspberrypi" />
  </a>
</p>

