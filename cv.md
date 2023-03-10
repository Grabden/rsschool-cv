# Dolgor Budatsyrenova

### Junior Frontend Developer
***
### Contact information:
* **Phone:** +79956592704
* **E-mail:** budatsyrenova.dolgor@mail.ru
* **Telegram:** @LilianaGrabde
* **Discord:** #Null1824
***
### About myself:
After graduating from university I realized that I need to learn a lot in order to master the initial skills of a front-end developer.
I hope that in the future I can raise my diploma with pride and not with shame.
***
### Skills and Proficiency:
* HTML5, CSS3
* JavaScript Basics
* Git, GitHub
* Mathematics
***
### Code Example:
**Two to One:** Take 2 strings s1 and s2 including only letters from a to z. Return a new sorted string, the longest possible, containing distinct letters - each taken only once - coming from s1 or s2.
```
function longest(s1, s2) {
  // your code
  var s=s1+s2,k=[];
  for(var i=0;i<s.length;i++)
    k[i]=s[i];
  k=k.sort();
  s=k[0];
  for(var i=1;i<k.length;i++){
    if(k[i]!=k[i-1])s=s+k[i];
  }
  return s;
}
```
***
### Courses:
* RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)
***
### Languages:
* English - A2
* Russian - native.
