## Project 1

In this project, we had an introduction and learned about server-side JavaScript, using node.js



### Source Code

    
    let date = new Date();
    let weekday = date.getDay();
    let weekdays = ['Sunday', 'Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday'] 
    console.log(weekdays[weekday]);



    function getRandomInteger(min, max) {
      return Math.floor(Math.random() * (max - min) + min);
    }

    //array
    let letters = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z'];

    function randomString() {
        let stringer = '';
        for (i = 0; i <= (getRandomInteger(5,26)); i++) {
            stringer = stringer + letters[getRandomInteger(0,26)];
        }

        return stringer;
    }

    console.log(randomString());
