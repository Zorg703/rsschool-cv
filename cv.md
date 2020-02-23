1. Sergei Mordas;
2. email: sergei.mordas@gmail.com; phone number: +375447593960
3. 29 years old. Friendly, disciplined, have good analytical skills.
4. Java, SQL, HTML, CSS, GIT, Spring Framework, Spring Boot, Maven
5. fun main() {
       println(whatShouldIDoToday("happy"))
   }
   
   fun whatShouldIDoToday(mood: String, weather: String = "sunny", temperature: Int = 24) : String {
       return when {
           isMoodAndWeatherForWalk(mood, weather)-> "go for a walk"
           mood == "sad" && weather == "rainy" && temperature == 0 -> "stay in bed"
           isTemperatureForSwimming(temperature) -> "go swimming"
           isMoodAndWeatherForCinema(mood, weather)-> "go to the cinema"
           else -> "Stay home and read."
       }
   }
   
   
   fun isTemperatureForSwimming(temperature: Int) = temperature > 35
   
   fun isMoodAndWeatherForWalk(mood: String, weather: String) =  mood == "happy" && weather == "Sunny"
   
   fun isMoodAndWeatherForCinema(mood: String, weather: String) =  mood == "boring" && weather == "rainy"
6.  Link on my github: https://github.com/Zorg703
    
7.  - Java Fundamentals course 2017;
        - Java EE EPAM course 2018;
        - Java Lab Epam 2018;      
8. Level: B1        