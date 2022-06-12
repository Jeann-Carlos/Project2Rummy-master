

<div id="top"></div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#preparation">Preparation</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
Rummy is a collection of matching card games with similar gameplay centered on matching cards of the same rank, sequence, and suit. In any variation of rummy, the purpose is to create melds, which can be sets (three or four of a kind of the same rank) or runs (three or more sequential cards of the same suit).
This prject is an interactive version of the card game Rummy. This is the work of another project where they supplied some basic UI implementation, I worked only on the implementations of said projet.
See repository [here](https://github.com/Jeann-Carlos/Project2Rummy-master.git).
<p align="right">(<a href="#top">back to top</a>)</p>



## Preparation

1. Clone this repository 
   ```
   git clone https://github.com/Jeann-Carlos/cslabproject.git
   ```
   
2. Change your directory to the project's

   Once you are in, use the terminal to clone the project:
   ```
   cd ./Project2Rummy-master
   ```
3. Compile the sources
   ```
   javac.exe ./proj2.proj2.java
   ```  
4. To run:  
   ```
   java.exe ./proj2.proj2.java
   ```
  <p align="right">(<a href="#top">back to top</a>)</p>
 <!-- USAGE EXAMPLES -->
## Usage

The program can be run with 2 arguments the first one is the number of AI controlled players. The second argument is -h if you want to activate the logger.  

General Usage:
 ```
   java.exe ./proj2.proj2.java [Number of Non-AI players, (0,2) ] [Logging Services, -h ] #Logs are stored in log.txt on the project directory
 ```

Examples:
 ```
   java.exe ./proj2.proj2.java 2 -h # 2 Players (no AI) with the logging service
 ```
 ```
   java.exe ./proj2.proj2.java 0  # 0 Players (All AI) with no logging service
 ```

### Quick View
![Screenshot 2022-06-10 235238](https://user-images.githubusercontent.com/56929989/173177253-f7f50ebf-3290-48f4-b73d-25db44d42a0c.png)  

  <p align="right">(<a href="#top">back to top</a>)</p>
  
    
<!-- CONTACT -->
## Rummy Rules
1. Each player is dealt 9 cards from the stock pile (i.e. Deck)
2. The next card from the Deck is turned face-up and placed in the discard pile (i.e. Stack).
3. In each turn, a player:
   1. Draws from the Deck or Stack
   2. Does some optional actions:
      - Lay a Set on the table
      - Lay a Run on the table
      - Lay cards that fit in Sets or Runs already on the table
   3. Discards to the Stack
      - (~~Though, if a player is able to lay all remaining cards on the table at the end of a turn, the discard is optional~~)?
4. The game is over when either:
   - One player is out of cards
     - In which case, said player is crowned winner
   - The cards from the stock pile are exhausted
     - If the cards from the Deck are exhausted, all players count the points remaining in their hands, and the lowest value hand wins (ties are possible!)


### User Interface

![Screenshot 2022-06-11 001238](https://user-images.githubusercontent.com/56929989/173178011-737930a0-4934-4fe4-b538-779123722368.png)

<p align="right">(<a href="#top">back to top</a>)</p>






<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>





<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

The only references used to construct this project were:

1. [Official Java Tutorials & Documentation](https://docs.oracle.com)
2. [Stack Overflow](https://stackoverflow.com)

I didn't receive any help from other people nor third parties.

I didn't help anyone else in the group, as of the time of writing.

<p align="right">(<a href="#top">back to top</a>)</p>


