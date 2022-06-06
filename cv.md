# rsschool-cv
# **My CV Project**
## **Tursynbekov Temiraln**
### *Student*
![](https://media-exp2.licdn.com/dms/image/C4E03AQHjDnPmJHnDzQ/profile-displayphoto-shrink_400_400/0/1652094339218?e=1660176000&v=beta&t=pTCFYtJBW2X_FirbNq4Xb8zBkMoB8MKdGAHl0_xwOIE)
___

### Contact information:
**Phone:** +77026180983

**E-mail:** ttursynbekov07@gmail.com

**Telegram:** @eisenchamp

[LinkedIn](https://www.linkedin.com/in/temirlan-tursynbekov-b910641b8/)

[Instagram](https://www.instagram.com/eisenchamp/)

___

### Briefly About Myself:
I'm 19 years old. I am studying computer science and I want to become one of the people who will contribute to the development of society through their skills.

___

### Skills and Proficiency:
- Microsoft Office (Word, Excel, PowerPoint)
- Working with the Linux operating system (Ubuntu)
- Data Structures and Algorithms
- С
- С++ 
- Pyton

___

### Code example:
**'Find illegal dollar sign' from university tasks:** Given a file with a text, find if there are any dollar signs. If there are such elements, return "illegal dollar sign in line" and detect in which line the sign was found.
```
#include <iostream>
#include <stdio.h>

struct openfile{
private:
	FILE *f;
public:
	openfile(const char*c){
		f=fopen (c, "r");
	}	
	bool isopen(){
		if (!f){
			std::cout<<"could not open the file\n";
			return false;
		}else{
			return true;
		}
	}
	int getchar(){
		return getc(f);
	}
	
	~openfile(){
		fclose(f);
	}
};

int main (int argc, char **argv){
	openfile opn = "myfile.in";
	std::cout<<opn.isopen()<<"\n";
	int linenr = 1;
	int c = opn.getchar();
	while (c!=EOF){
		if (c=='$'){
			std::cout << "illegal dollar sign in line "<< linenr<<"\n";
			return 0;
		}
		if (c=='\n'){
			linenr++;
		}
		c = opn.getchar();
	}
	return 0;
}
```
___

### Educatuion:
> BIL №1 | 2015-2020
- The owner of the distinctive sign ["Altyn Belgi"](https://ru.wikipedia.org/wiki/Алтын_белги)
- Class President
- Gold medalist of the regional competition among schools in intellectual games
- One of the leaders of the Reading club

> Nazarbayev University | Computer Science | 2020 - present
- Student of the School of Engineering and Digital Sciences
- Member of the debate club "Nomad Club"

___

### Work Experience:
> English Language Tutor | "Poliglot" Centre | 1 month | 2021
- Teaching middle school students three times a week
- Preparing students for exams
- Creating lesson plans for students

___

### Languages:
- Kazakh - Native
- Russian - Second Native
- English - Advanced
- German - Upper Intermediate
- Turkish - Intermediate

___

### Hobbies:
- Reading \| Classic books \| 30 - 40 books a year 
- Learning to play the ukulele
- TikTok \| 68.1k subscribers
- Drawing
- Singing
- Dancing
