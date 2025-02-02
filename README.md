### Table of Contents
- [Table of Contents](#table-of-contents)
- [What is Competitive Programming(CP)?](#what-is-competitive-programmingcp)
- [What is a Problem?](#what-is-a-problem)
- [The Ultimate Question: Why should I start Competitive Programming?](#the-ultimate-question-why-should-i-start-competitive-programming)
- [The Secret](#the-secret)
- [Seriously vs Sincerely](#seriously-vs-sincerely)
- [What Progress is Really Like](#what-progress-is-really-like)
- [Which language should I use for CP?](#which-language-should-i-use-for-cp)
- [Where to write codes? What are the best IDEs?](#where-to-write-codes-what-are-the-best-ides)
- [Competitive Programming Platforms](#competitive-programming-platforms)
- [Details about problem statements, how contests work and the rating system on Codeforces (and a few other platforms) <a name = "ratingsys"></a>](#details-about-problem-statements-how-contests-work-and-the-rating-system-on-codeforces-and-a-few-other-platforms-)
- [What to do if I don't know how to solve a problem?](#what-to-do-if-i-dont-know-how-to-solve-a-problem)
- [How to check others solutions?](#how-to-check-others-solutions)
- [How to practice a problem efficiently?](#how-to-practice-a-problem-efficiently)
- [Virtual Contests](#virtual-contests)
- [Kidlin's Law](#kidlins-law)
- [[Contest]Solve some very basic problems.](#contestsolve-some-very-basic-problems)
- [[Editorials and Codes] Check how to solve the problems of Contest 3](#editorials-and-codes-check-how-to-solve-the-problems-of-contest-3)
- [FAQ](#faq)
- [Important Notes](#important-notes)
- [Getting into Competitive Programming](#getting-into-competitive-programming)
- [Tutorial](#tutorial)
- [Life Hack(if you are from Bangladesh)](#life-hackif-you-are-from-bangladesh)
- [How to do Topicwise Practice?](#how-to-do-topicwise-practice)
- [Topic List (As you are feeling lazy to collect them by yourself!)](#topic-list-as-you-are-feeling-lazy-to-collect-them-by-yourself)
- [Code Library](#code-library)
- [The Art of Debugging](#the-art-of-debugging)
- [Stress Testing](#stress-testing)

### What is Competitive Programming(CP)?
  Writing code to solve problems or tasks is the essence of programming. Competitive programming turns this into a sport, with competitors competing (typically online) to solve a bunch of such problems in a restricted period of time.

  "A programming competition generally involves the host presenting a set of logical or mathematical problems, also known as puzzles, to the contestants (who can vary in number from tens to several thousand), and contestants are required to write computer programs capable of solving each problem. Judging is based mostly upon several problems solved and time spent for writing successful solutions." - Wikipedia

### What is a Problem? 
  A problem is often based on arithmetic, logic, and/or algorithms and looks somewhat like [this](https://codeforces.com/problemset/problem/630/A). Such challenges often include a statement (detailing the task), the input and output format, and input, time and memory constraints.

  Try to understand [this](https://codeforces.com/problemset/problem/630/A) problem, read the statement carefully, check the input-output constraints and solve this. When you get the idea of how to solve it, then code it and submit it to get your first AC (Accepted solution).

  Here is the code for the problem in C++.

  ``` c++
  #include<bits/stdc++.h>
  using namespace std;

  int main() {
    long long n; cin >> n;
    cout << 25 << '\n';
    return 0;
  }
  ```

### The Ultimate Question: Why should I start Competitive Programming?
  Well, I believe that the ultimate goal of my existence is to be happy. And I have learned from many well-established people that getting a great job or being famous or other common stereotypical goals won't make you happy as when you get used to those they become meaningless.

  I think happiness is living your present with excitement.

  That being said, now your main goal is to find something that will make you happy. There are lots of things you can do like being a musician or an artist etc. For me it was CP. I can lose myself in CP for hours and hours and still hold my excitement. A good contest is enough to make my day.

  Man, I am not saying that you have to choose CP too. Find anything that suits you well, delve into that and maybe you will find peace.

  Because I wanna spend my precious time on something so that in the end I can say with Heisenberg, "I did it for me. I liked it, I was good at it, and I was really... I was alive".
  
  **So what kinda benefits you will get by doing CP?**
    - Fun and excitement(tons of it).
    - "Competitive programming builds the basics in you. You became so expert in coding anything that learning framework then becomes a very very easy task. Because when you learn to read the codes of hard or advanced algorithms, what can be more complex than those?  

"CP programming makes you versatile, so you can move from any stack to other. But when you only learn a specific framework or stack, your knowledge gets bounded.
  You can compare learning any natural language with this. Let's say you want to learn German/English. You need to learn grammar first then you can write a paragraph. In coding, you can think of CP programming as grammar learning and frameworks as paragraph writing! When you know grammar you can write a paragraph on any topic.
  Even after a good or average (not the best) career in CP, you will find the database, distributed system, machine learning topics very much understandable to you."- Raihat Zaman Neloy
  - You will find Interview problems much much easier if you do CP. Problem-solving skill is required in interviews and CP is the best and most exciting way to learn problem-solving.
  - "Competitive programming is recognized and supported by several multinational software and Internet companies, such as Google and Meta (Facebook). Several organizations host programming competitions on a regular basis." - Wikipedia
  - [and many more...](https://www.quora.com/What-have-you-gained-from-competitive-programming-Did-you-go-into-research-Did-it-help-you-in-any-aspect-as-a-software-engineer-Did-it-help-you-get-an-in-depth-knowledge-of-a-programming-language-Did-it-affect-your-problem-solving-skills)

  Let's discuss something if you think CP is the thing that you wanna do.

  Many of us set this goal like I wanna be red and continuously **looking at the goal** and not enjoying our **current** hard works. I am not red but I can guarantee myself that when I will be red I will be happy for a day or two and will get used to it. So what was my 3-4 years of hard work all about? Just a day of excitement? I don't believe in so. Wouldn't it be great if I could live those 3-4 years of my life with excitement? Well yes. This is what I am currently doing. I am living in the present, working hard and whether I become successful or not I will still be happy as I was **alive** throughout the whole process and lived my life to the fullest.

  May you find that something that you have been looking for throughout your life!  

### The Secret
  Not everyone has the privilege to do the things that they enjoy doing. If you have that privilege, then it's really cool. But most people don't have that privilege. So "Instead of doing things you enjoy, learn to enjoy the things you do". And CP is one of the things that you can easily fall in love with.

### Seriously vs Sincerely
  If you find yourself approaching things too seriously like it's no fun playing a game if you take it "too seriously". So if you want to have fun, you should switch to approaching things sincerely, like you are still gonna give it all, but you are gonna recognize that this is a game and you are gonna try and enjoy yourself while doing it. This philosophy also applies in CP. Watch [this](https://www.youtube.com/watch?v=FbSNfj2S6Pw) for more.

### What Progress is Really Like
  Imagine that you have an ice cube sitting on the table in front of you.

  The room is cold and you can see your breath. It is currently twentyfive degrees. Ever so slowly, the room begins to heat up.

  Twenty-six degrees. <br>
  Twenty-seven. <br>
  Twenty-eight.

  The ice cube is still sitting on the table in front of you.

  Twenty-nine degrees. <br>
  Thirty. <br>
  Thirty-one.

  Still, nothing has happened.

  Then, thirty-two degrees. The ice begins to melt. A one-degree shift, seemingly no different from the temperature increases before it, has unlocked a huge change. 

  Breakthrough moments are often the result of many previous actions, which build up the potential required to unleash a major change. This pattern shows up everywhere. Cancer spends 80 percent of its life undetectable, then takes over the body in months. Bamboo can barely be seen for the first five years as it builds extensive root systems underground before exploding ninety feet into the air within six weeks.

  Credit: The book Atomic Habit by  James Clear

  So don't get depressed after starting CP. It takes time to get your work reflected on your progress.
### Which language should I use for CP?
  Most Competitive Programmers (more than 95%) use C++ mostly because it's quite faster than other languages and it has some great built-in libraries(Standard Template Library (STL)) to ease your life. There are also many [other reasons](https://www.quora.com/Why-do-competitive-programmers-prefer-to-use-C++-instead-of-Java-in-the-programming-contests) for using C++.

  You can also use other languages too but for CP C++ is better. Languages are just tools and it doesn't take more than a few days to understand the basics of a language.

  Note that you don't have to be a master in C++ to start your CP journey. If you know the basics i.e. variables, data types, operators, conditions, functions and loops, then you are ready to start CP. You can learn them from [here](https://www.javatpoint.com/cpp-tutorial) or any of your favourite youtube channels.

### Where to write codes? What are the best IDEs?

  IDEs are where you will write your codes. You can use Sublime Text, Codeblocks, VS Code or any other IDE that you like. 

  I use Sublime Text. Check [this](https://www.geeksforgeeks.org/setting-up-sublime-text-for-cpp-competitive-programming-environment/) to set up C++ in Sublime Text for Competitive Programming. Check [this](https://github.com/the-hyp0cr1t3/CC/blob/master/Sublime%20Text%20Setup.md) to set up useful tools and snippets for Sublime Text and [this](https://kirankoduru.github.io/python/sublime-text-ninja.html) to find useful shortcuts.

  <details> <summary> Your sublime text should be something like this </summary>
  <a href="https://ibb.co/xfYv6Tk"><img src="https://i.ibb.co/3MvXcZ3/image.png" alt="image" border="0"></a>
  </details>

  Check [this](https://medium.com/@chinmaykulkarni8/how-to-setup-visual-studio-code-for-c-c-java-python-competitive-programming-angular-22fdc9b1f4c6) to setup C, C++, Java, Python in Visual Studio Code for Competitive Programming.


### Competitive Programming Platforms

  The most famous CP platform is [Codeforces](https://codeforces.com/). Check [this](https://blog.codingblocks.com/2019/sites-and-tools-for-competitive-programming/) to know about more platforms.

### Details about problem statements, how contests work and the rating system on Codeforces (and a few other platforms) <a name = "ratingsys"></a>

  Check [this](https://github.com/the-hyp0cr1t3/CC/blob/master/Competitve%20Programming%20Platforms.md) to get a detailed understanding of whats in a problem, what is meant by different verdicts (AC, WA, TLE, MLE, CE etc) and how contests work.

### What to do if I don't know how to solve a problem?
  Most of the problems have editorials/tutorials. The tutorial link is normally attached to the problem statement. In particular, on Codeforces, you can find the link to the tutorial at the lower right side of the problem statement. 
  <details> <summary> Example </summary>
  <a href="https://ibb.co/MRxm4XK"><img src="https://i.ibb.co/cNSjHmR/tutorial.jpg" alt="tutorial" border="0"></a>
  </details>

  Also, **join this discord server(if you are from Bangladesh) to get help**. Link: [Bangladesh CP Server](https://discord.gg/hDSMZATsrM)

### How to check others solutions?
  Check [this](https://codeforces.com/blog/entry/17012) to check solutions for a specific problem on Codeforces.

  For other platforms the way is similar. Just go to the submissions page for that problem and click on the ID of the submission.

  You can follow other users on Codeforces and make them friends (click the star button on the right of the username on CF) and check their solutions using the "friends only" button. I like the coding styles of the following users:
  - [neal](https://codeforces.com/profile/neal)
  - [YouKn0wWho](https://codeforces.com/profile/YouKn0wWho)
  - [mango_lassi](https://codeforces.com/profile/mango_lassi)
  - [jiangly](https://codeforces.com/profile/jiangly)
  - [tourist](https://codeforces.com/profile/tourist)
  - [Anachor](https://codeforces.com/profile/Anachor)
  - [Bruteforceman](https://codeforces.com/profile/Bruteforceman)
  - [Others](https://codeforces.com/blog/entry/77865)

### How to practice a problem efficiently?
  - First of all, you should try to solve it by yourself.
  - At the first glance, it may look like you have no idea what that random alien-made problem is asking you to do. But take your time. Always try to solve the problem using brute force. After that try to make your solution more efficient. 
  - Ok, so still you have no idea how to solve the problem? Try to look at it from a whole new angle.
  - "Keep trying while you have new ideas, then look up the editorial/tutorial after **15+ minutes of being completely stuck**." - Kamil Debowski
  - To be more precise, if you think you are getting into the solution, then take more time and try to solve it. But if you have no clue on how to solve it, then what is the point of wasting your valuable time? It will only slow down your improvement process.
  - After solving a problem by looking at the editorial/others codes, **think about why your way of thinking was not correct, what did you miss**. This is reallyyyy important.
  - Time to implement the problem. Try not to use any unnecessary macros. Try to make it more readable. It will help you debug the solution.
  - After that read implementations of some skilled users (searching for some useful tricks or really nice implementations). **This part is really important which will significantly improve your skill.**
  - If the problem uses a new idea/trick/algorithm which is a classic one i.e. it might be helpful in future then try to write that down so that in future you can easily access it.

### Virtual Contests
Virtual contests will give you a real-time experience. It enables the users to run the past contests in a special mode that would imitate a real competition. It feels just like a real contest with real contestants competing alongside the participant who writes a virtual contest. It won't affect your rating.

Do at least 3 virtual contests per week. Just pick any time and start a virtual contest from here: [link](https://codeforces.com/contests).

Do upsolve. Problems you can't solve during a contest but was in your range should be solved after the contest. What is the meaning of a contest if you don't learn something that wasn't already known to you?

### Kidlin's Law
  Kidlin's law: If you can write the problem down clearly then the matter is already half solved.

  This is also the same here in CP. First, understand what the problem asks you to do. Then proceed to solve it. If you understand it correctly, then you are half done. So don't start solving without understanding what the problem demands.

### [Contest]Solve some very basic problems.
  Get familiar with problem-solving by solving these problems. You won't need to know anything other than the basics of a language to solve them. <br>
  Goal: Solve at least 30 problems in total from the following contests. 

  - Contest 1: [link](https://codeforces.com/group/MWSDmqGsZm/contest/219158)
  - Contest 2: [link](https://codeforces.com/group/MWSDmqGsZm/contest/219432)
  - Contest 3: [link](https://vjudge.net/contest/468964)

### [Editorials and Codes] Check how to solve the problems of Contest 3
  Credit: @MehediMubin, @tahmidarefin and @Tofayel and me
  <details> <summary> smash me </summary>
  <b>1. Problem A</b>

  Editorial: [link](https://img.atcoder.jp/abc169/editorial.pdf)
  <details> <summary> Code(C++) </summary>

  ```c++
  #include<bits/stdc++.h>
  using namespace std;

  int main() {
    int a, b; cin >> a >> b;
    cout << a * b << '\n';
    return 0;
  }
  ```
  </details>
  <br>

  <b>2. Problem B</b>

  Editorial: [link](https://atcoder.jp/contests/abc209/editorial/2242)
  <details> <summary> Code(C++) </summary>

  ```c++
  #include<bits/stdc++.h>
  using namespace std;

  int main() {
    int a, b; cin >> a >> b;
    cout << max(0, b - a + 1) << '\n';
    return 0;
  }
  ```
  </details>
  <br>

  <b>3. Problem C</b>

  Editorial: [link](https://img.atcoder.jp/abc124/editorial.pdf)
  <details> <summary> Code(C++) </summary>

  ```c++
  #include<bits/stdc++.h>
  using namespace std;

  int main() {
    int a, b; cin >> a >> b;
    cout << max({a + (a - 1), b + (b - 1), a + b}) << '\n';
    return 0;
  }
  ```
  </details>
  <br>

  <b>4. Problem D</b>

  Editorial: [link](https://atcoder.jp/contests/abc226/editorial/2903)
  <details> <summary> Code(C++) </summary>

  ```c++
  #include<bits/stdc++.h>
  using namespace std;

  int main() {
    double d; cin >> d;
    cout << round(d) << '\n';
    return 0;
  }
  ```
  </details>
  <br>

  <b>5. Problem E</b>

  Editorial: [link](https://atcoder.jp/contests/abc222/editorial/2757)
  <details> <summary> Code(C++) </summary>

  ```c++
  #include<bits/stdc++.h>
  using namespace std;

  int main() {
    int n; cin >> n;
    if (n < 10) cout << "000" <<  n << '\n';
    else if (n < 100) cout << "00" <<  n << '\n';
    else if (n < 1000) cout << "0" <<  n << '\n';
    else cout << n << '\n';
    return 0;
  }
  ```
  </details>
  <br>

  <b>6. Problem F</b>

  Editorial: [link](https://img.atcoder.jp/abc125/editorial.pdf)
  <details> <summary> Code(C++) </summary>

  ```c++
  #include<bits/stdc++.h>
  using namespace std;

  int main() {
    int a, b, t;
    cin >> a >> b >> t;
    cout << t / a * b << '\n';
    return 0;
  }
  ```
  </details>
  <br>

  <b>7. Problem G</b>

  Editorial: [link](https://atcoder.jp/contests/abc220/editorial/2700)
  <details> <summary> Code(C++) </summary>

  ```c++
  #include<iostream>
  using namespace std;
  int main(){
      int a, b, c;
      cin >> a >> b >> c;
      if((a - 1) / c == b / c) cout << -1 << '\n';
      else cout << c * (b / c) << '\n';
      return 0;
  }
  ```
  </details>
  <br>

  <b>8. Problem H</b>

  Editorial: [link](https://codeforces.com/blog/entry/43392)
  <details> <summary> Code(C++) </summary>

  ```c++
  #include<iostream>
  using namespace std;
  int main(){
      int a, b, c;
      cin >> a >> b >> c;
      for(int i = 0; i <= 5000; i++){
          for(int j = 0; j <= 5000; j++){
              if(i * a + j * b == c){
                  cout << "Yes" << '\n';
                  return 0;
              }
          }
      }
      cout << "No" << '\n';
      return 0;
  }
  ```
  </details>
  <br>

  <b>9. Problem I</b>

  Editorial: [link](https://atcoder.jp/contests/abc199/editorial/1165)
  <details> <summary> Code(C++) </summary>

  ```c++
  #include<iostream>
  using namespace std;
  int main(){
      int a, b, c;
      cin >> a >> b >> c;
      cout << ((a * a + b * b) < c*c ? "Yes" : "No") <<'\n';
      return 0;
  }
  ```
  </details>
  <br>

  <b>10. Problem J</b>

  Editorial: [link](https://atcoder.jp/contests/abc193/editorial/822)
  <details> <summary> Code(C++) </summary>

  ```c++
  #include<iostream>
  #include<iomanip>
  using namespace std;
  int main(){
      double a, b, ans;
      cin >> a >> b;
      ans = (a - b) / a * 100.0;
      cout << fixed << setprecision(3) << ans << '\n';
      return 0;
  }
  ```
  </details>
  <br>

  <b>11. Problem K</b>

  Editorial: [link](https://img.atcoder.jp/abc152/editorial.pdf)
  <details> <summary> Code(C++) </summary>

  ```c++
  #include<iostream>
  using namespace std;
  int main(){
      int n, m;
      cin >> n >> m;
      cout << (n == m ? "Yes" : "No") << '\n';
      return 0;
  }
  ```
  </details>
  <br>

  <b>12. Problem L</b>

  Editorial: [link](https://codeforces.com/blog/entry/24160)
  <details> <summary> Code(C++) </summary>

  ```c++
  #include<iostream>
  using namespace std;
  int main(){
      long long n;
      cin >> n;
      cout << 25 << '\n';
      return 0;
  }
  ```
  </details>
  <br>

  <b>13. Problem M</b>

  Editorial: [link](https://atcoder.jp/contests/abc214/editorial/2444)
  <details> <summary> Code(C++) </summary>

  ```c++
  #include<bits/stdc++.h>
  using namespace std;

  int main(){
      int S, T; cin >> S >> T;
      int cnt = 0;
      for(int a = 0; a <= S; a++){
          for(int b = 0; a+b <= S; b++){
              for(int c = 0; a+b+c <= S; c++){
                  if(a*b*c <= T) cnt++;
              }
          }
      }
      cout << cnt << endl;
  }


  ```
  </details>
  <br>

  <b>14. Problem N</b>

  Editorial: [link](https://codeforces.com/blog/entry/21590)
  <details> <summary> Code(C++) </summary>

  ```c++
  #include <iostream>
  using namespace std;
  typedef long long ll;

  int T;
  ll N;

  int main()
  {
    cin >> T;

    for (int t = 0; t < T; t++)
    {
      cin >> N;

      ll power = 1;
      while (2 * power <= N)
        power *= 2;

      cout << N*(N + 1) / 2 - 2 * (power * 2 - 1) << "\n";
    }

    return 0;
  }

  ```
  </details>
  <br>

  <b>15. Problem O</b>

  Editorial: [link](https://img.atcoder.jp/abc051/editorial.pdf)
  <details> <summary> Code(C++) </summary>

  ```c++
  #include<bits/stdc++.h>
  using namespace std;

  int main() {
    int k, s; cin >> k >> s;
    int count = 0;
    for (int x = 0; x <= k; x++) {
      for (int y = 0; y <= k; y++) {
        int z = s - x - y;
        if (z >= 0 and z <= k) {
            count++;
          }
      }
    }
    cout << count << '\n';
    return 0;
  }
  ```
  </details>
  <br>

  <b>16. Problem P</b>

  Editorial: [link](https://codeforces.com/blog/entry/2393)
  <details> <summary> Code(C++) </summary>

  ```c++
  #include<bits/stdc++.h>
  using namespace std;
  typedef long long ll;

  string s;

  int main()
  {
      cin.sync_with_stdio(0);

      int sum = 0;
      cin >> s;
      for (int i = 0; i < s.size(); i++) sum += s[i] - '0';
      int ans = 1;
      if (s.size() == 1) ans = 0;

      while (sum > 9)
      {
          int temp = sum, newsum = 0;
          while (temp)
          {
              newsum += temp % 10;
              temp /= 10;
          }
          sum = newsum;
          ans++;
      }

      cout << ans << endl;

      return 0;
  }


  ```
  </details>
  <br>

  <b>17. Problem Q</b>

  Editorial: [link](https://codeforces.com/blog/entry/610)
  <details> <summary> Code(C++) </summary>

  ```c++
  #include <iostream>
  #include <cstdio>

  using namespace std;

  int fact(int n) {

      int r = 0;
      for(int i = 2; i * i <= n; ++i) {
          if(n % i == 0) {
              r++;
              while(n % i == 0) n /= i;
          }
      }
      if(n > 1)
          r++;
      return r;
  }

  int main() {

      int n, c = 0;

      cin >> n;

      for(int i = 1; i <= n; ++i) {
          if(fact(i) == 2)
              c++;
      }
      cout << c << endl;

      return 0;
  }


  ```
  </details>
  <br>

  <b>18. Problem R</b>

  Editorial: [link](https://codeforces.com/blog/entry/6662)
  <details> <summary> Code(C++) </summary>

  ```c++
  #include <iostream>

  using namespace std;

  int main()
  {
      int y;
      cin >> y;
      while (true)
      {
          y += 1;
          int a = y / 1000;
          int b = y / 100 % 10;
          int c = y / 10 % 10;
          int d = y % 10;
          if (a != b && a != c && a != d && b != c && b != d && c != d)
          {
              break;
          }
      }
      cout << y << endl;
      return 0;
  }

  ```
  </details>
    </details>
    
  REMEMBER THAT SOLVING MORE PROBLEMS IS THE KEY

### FAQ
  - [What is the key to CP?](https://codeforces.com/blog/entry/47516)
  - [Regarding Interviews and Jobs](https://redgreencode.com/cpwiki/Category:FAQs_about_interviews_and_jobs)
  - [CP or Development?](https://redgreencode.com/cpwiki/Should_I_spend_my_time_on_competitive_programming_or_real-world_software_development%3F)
  - [I need Advice](https://redgreencode.com/cpwiki/What_advice_does_(person)_have_for_competitive_programming_success%3F)
  - [When will I be a good CPer?](https://codeforces.com/blog/entry/53341?#comment-373965)

### Important Notes
  - **Exercise** (at least running) and drink more water. It will surprisingly boost up your learning capability.
  - **Getting AC is not the final goal, learning something new is the final goal**. Exactly, for this reason, people solve thousands of problems but can't get better. You need to solve harder problems than your current level so that you can learn something new by solving that problem. Also, after you solve a problem, try to do it more efficiently if possible, look at others solutions. This way you will learn better and become better faster in the long run.
  - After solving a problem, **think about why your way of thinking was not optimal**. This is important too.
  - **SOLVE MORE PROBLEMS**.

### Getting into Competitive Programming
  - [Getting into CP](https://github.com/the-hyp0cr1t3/CC)
  - [Basic Blocks](https://www.hackerearth.com/practice/notes/getting-started-with-the-sport-of-programming/ )
  - [Book](https://cses.fi/book/book.pdf)

### Tutorial
  - [A way to Practice Competitive Programming : From Rating 1000 to 2400+](https://drive.google.com/file/d/1J2x8pIYQ3MXANgvzOgBciWd3d79j_Exa/view)

**Note: If your Codeforces rating is not at least 1600 then the aftermentioned topicwise practice is not needed, just learn basic stuffs and follow the tutorial linked above.**
 
---
### Life Hack(if you are from Bangladesh)
If you want a complete guideline like this for EVERYTHING about CP and you are from Bangladesh, then you can check out my academy and enroll in some courses that fits you well. 

Link: [YouKn0wWho Academy](https://academy.shahjalalshohag.com/). 

Actually the whole part of this repo till now is taken from a **single class** from one of my academy courses!

--- 
### How to do Topicwise Practice?
  1. Create a topic list(every possible category, from easy to advanced).
  2. Select a topic.
  3. Learn the topic.
  4. Solve lots of problems about that topic.
  5. Go to ii.

  And of course, participate in every possible contests in every online judge.                                                            
  
### Topic List (As you are feeling lazy to collect them by yourself!)
- [The Ultimate Topic List (with Resources, Problems and Templates)](https://codeforces.com/blog/entry/95106)

### Code Library
- [Almost all the important templates that you will need in CP](https://github.com/ShahjalalShohag/code-library)

### The Art of Debugging
  - Run with n=1.
  - Check overflow(long long vs int).
  - Check all array bounds.
  - Check if m, n aren’t misused.
  - Printed enough new lines or extra new lines?
  - Make sure output format is right(including YES/NO vs Yes/No or
  newline vs spaces).
  - Have you cleared the vectors ?
  - Make sure two ints aren’t multiplied to get a long long.
  - Output enough digits after decimal point.
  - Check the constraints again.
  - When using multiple dfs recursions check if inside one dfs another dfs
  is called or not.
  - Shouldn't you print the case number?
  - Are you using the correct mod value?
  - "I spent a lot of my time debugging my solution without any success,
  after the contest I discovered that the obstacles in the input is 'x'
  (small one) while I was thinking it was 'X' (capital), I lost a bronze
  medal because of it :(" - kingofnumbers
  - Set or multiset?
  - Different Variables with the same name?
  - Inside 2d loop are you using i++ instead of j++?
  - Are you using ceil function? Then remove it!
  - Is inf large enough?
  - For multiple queries are you returning 0 inside the queries?
  - For max and min have you initialized the values by a good enough
  value?
  - Are you using the local variable of the same name when global variable was
  required to be used?
  - "Declared a counter of type char instead of int , resulted in passing of
  pretests and failing of system test. :)" - A random CF user
  - "I subtracted 1 in a for loop from v.size(). Guess what happened when
  the input vector is empty?" - A random CF user
  - "for (int i = n - 1; i--; i >= 0)
  instead of:
  for (int i = n - 1; i >= 0; i--)
  It passed pretests and failed systests" - A random CF user
  - Are you using memset correctly?
  - Use bool operators using brackets. Beware!!! E.g. ans = ans + k == 0 vs ans = ans + (k == 0).
  - Have you deleted debug(x) lines? It might get you TLE!
  - It may be scanf("%d" , x). where &x is missing.
  - Instead of printing NO printed N0. (with a zero).
  - Are you erasing values from a set or an stl while parallelly traversing
  the elements of the stl? Please don’t. This is not nice!
  - Don't use scanf or printf while using ios_base.
  - Still have no idea? Try to recode from scratch or see others solutions.
### Stress Testing
  - [Find a counter-test](https://ali-ibrahim137.github.io/competitive/programming/2020/08/23/Stress-Testing.html)

Also, remember to exercise and drink more water. It helps a lot. 

Good luck <a href="https://emoji.gg/emoji/8771_blobheart"><img src="https://emoji.gg/assets/emoji/8771_blobheart.png" width="16px" height="16px" alt="blobheart"></a>.
