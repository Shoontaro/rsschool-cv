## Molchanova Yuliya

### My contacts:
- +375292302329 
- Discord: Shoon#6009
- Telegram: @yumolchanova

***

### About me:
I want to find a job in web development. I tried various programming languages, but in the end I chose **js**. It hooked me with its freedom of action and a variety of possible projects.   

Briefly about my hobbies and traits of my character:  
- **Games** :  
    + Uriosity. 
    + Ability to divide complex tasks into simpler ones.
- **Reading** :
    + Good imagination.
    + Perseverance.
- **Handcraft** :
    + Diligence.
    + I know a good way to relax.
   
***

### My skills:

* C++
* C#
* Unity
* HTML/CSS
* Arduino
* Puthon
* JS
* Git
* SQL

***

### Code samples:

This code make hashtag generator.
* It must start with a hashtag (#).
* All words must have their first letter capitalized.
* If the final result is longer than 140 chars it must return false.
* If the input or the result is an empty string it must return false.

```JS
function generateHashtag (str) {
  if(str.length == 0){
  return false;
  }
  let arr = str.split(' ');
  if(arr[0] == ''){
  return false;
  }
  for(let i =0; i< arr.length; i++){
    if ( arr[i] == "" && arr[i+1] == ""){
    arr.splice(i, 1);
    }
    else if(arr[i] == "" && arr[i+1]!=""){
    arr.splice(i, 1);
      arr[i] = arr[i][0].toUpperCase()+arr[i].slice(1);
    }
    else{
      arr[i] = arr[i][0].toUpperCase()+arr[i].slice(1);
  }
  }
  
  arr.unshift( "#" );
  let string = arr.join('');
  if(string.length > 140){
    return false;
  }
  return string; 
}
```

***

### My experience: 


I have no work experience and I want to get it.

https://codepen.io/Shoontaro

***

### Education:

I am a student of the Belarusian State University. 
I study at the Faculty of Radiophysics and Computer Technologies.

***

### Language:

| English       |        B2       |
|:------------- |:---------------:

***


