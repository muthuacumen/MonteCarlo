<h1 align="center">🎲 10 Real-Life Applications of Monte Carlo Simulation 🎲</h1>

<h3 align="center">A Guide for Grade 9 Students (No Programming Required!)</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Level-Grade_9_Friendly-brightgreen?style=for-the-badge" alt="Grade 9 Friendly"/>
  <img src="https://img.shields.io/badge/Code_Required-None!-blue?style=for-the-badge" alt="No Code Required"/>
  <img src="https://img.shields.io/badge/Hands--On_Activities-10-orange?style=for-the-badge" alt="10 Activities"/>
</p>

---

> **You already know the core idea** from your red-card project: throw lots of random darts, flip lots of random coins,
> and the answers start appearing like magic. Now let's see where grown-ups use this
> exact trick to solve problems worth **millions of dollars** and even **save lives**. 🚀

---

## 🎬 Start Here: Watch These Videos First!

Before diving in, watch these beginner-friendly videos to refresh the core idea:

| # | Video | What You'll Learn |
|:-:|-------|-------------------|
| 🎯 | [**A Simple Solution for Really Hard Problems: Monte Carlo Simulation**](https://www.youtube.com/watch?v=slbZ-SLpIgg) | A crystal-clear intro to what Monte Carlo is and why it works |
| 🧮 | [**The Strange Math That Predicts (Almost) Anything** — Veritasium](https://www.youtube.com/watch?v=KZeIEiBrT_w) | How random simulations power Google, AI, and nuclear science |
| 🎂 | [**The Birthday Paradox** — Numberphile](https://www.youtube.com/watch?v=a2ey9a70yY0) | The surprising probability puzzle you explored in your notebook! |

---

## 📖 Quick Vocabulary Refresher

| Term | Simple Explanation |
|:----:|-------------------|
| **Simulation** | A pretend experiment you run many times to see what *usually* happens |
| **Random Trial** | One round of your experiment (one dart throw, one coin flip) |
| **Probability** | How likely something is to happen, from 0% (never) to 100% (always) |
| **Outcome** | The result you get from one trial |
| **Variable** | Something that can change each time (like the weather, or a dice roll) |

---

## ⛅ Application 1 — Weather Forecasting

<img src="https://img.shields.io/badge/Industry-Meteorology-4169E1?style=flat-square" alt="Meteorology"/>

### 🔍 The Real Problem

When the weather channel says *"There is a 40% chance of rain tomorrow"*, how do they get that number? They don't just guess!

### 🎲 How Monte Carlo Helps

Meteorologists feed current weather data (temperature, humidity, wind speed, air pressure) into computer models. But they know their measurements aren't perfect — a thermometer might be off by a degree, wind sensors have small errors. So they run the weather model **thousands of times**, each time slightly changing the starting measurements within realistic error ranges.

- If **4,000 out of 10,000** simulated tomorrows produce rain, they announce: **40% chance of rain**.

> [!TIP]
> **Real-World Fact:** The Met Office in the UK runs **24 different simulations** every single forecast to give you that "% chance of rain" on your weather app!

### 🌟 Why It Matters

Without Monte Carlo, forecasters would give you ONE prediction that could be totally wrong. With Monte Carlo, they give you a **range of possibilities** and how likely each one is.

### 🎮 Try It Yourself (No Code Needed!)

Roll a die to decide tomorrow's "weather":
- 🎲 Roll 1 or 2 = 🌧️ Rainy
- 🎲 Roll 3 or 4 = ☁️ Cloudy
- 🎲 Roll 5 or 6 = ☀️ Sunny

Roll 30 times and tally the results. You just ran a Monte Carlo weather forecast! Compare your percentages to the theoretical 33.3% for each.

### 📺 Watch & Learn
- 🔗 [How Weather Forecasting Works — ensemble models explained (Met Office)](https://www.youtube.com/results?search_query=Met+Office+ensemble+weather+forecast+probability+explained)

---

## ⚽ Application 2 — Predicting Sports Outcomes

<img src="https://img.shields.io/badge/Industry-Sports_Analytics-FF4500?style=flat-square" alt="Sports Analytics"/>

### 🔍 The Real Problem

Before a big basketball or cricket match, sports analysts predict which team will win. But a single game has so much randomness — a player could have a bad day, someone might get injured, the referee might make a controversial call.

### 🎲 How Monte Carlo Helps

Analysts take each team's stats (scoring average, defence rating, home-court advantage) and simulate the game **10,000 times**. In each simulation, random "luck factors" are added — maybe the star player shoots 5% better or worse than usual.

- If Team A wins **7,200 out of 10,000** simulated games, they are given a **72% chance** of winning.

> [!TIP]
> **Real-World Fact:** ESPN's "win probability" graphic that changes during a live game? That's Monte Carlo running in real time! 📊

### 🌟 Why It Matters

This is exactly how sports betting odds are calculated, and how ESPN and TSN make their pre-game predictions. Fantasy sports apps use this too!

### 🎮 Try It Yourself (No Code Needed!)

Pick two teams. Assign each player a "skill score" from 1–6. For each player, roll a die 🎲 — that's their performance in the game. Add up all the player scores for each team. The higher total wins. Play 20 "games" and see which team wins more often.

### 📺 Watch & Learn
- 🔗 [Monte Carlo Simulation for Sports Predictions](https://www.youtube.com/results?search_query=monte+carlo+simulation+sports+prediction+probability+beginner)

---

## 🎬 Application 3 — Movie & Video Game Design (Computer Graphics)

<img src="https://img.shields.io/badge/Industry-Entertainment_&_CGI-9932CC?style=flat-square" alt="Entertainment"/>

### 🔍 The Real Problem

In animated movies like those from Pixar (think *Inside Out* or *Toy Story*), light bounces off surfaces in complicated ways — it reflects, refracts, scatters, and creates shadows. Calculating the exact path of every light ray is impossibly slow.

### 🎲 How Monte Carlo Helps

Instead of tracing every possible light ray, the computer **randomly picks a sample of light paths** and traces only those. It's like our dartboard trick — instead of checking every single point, we check random ones and the picture becomes clear.

This technique is called **Monte Carlo Ray Tracing**, and it's the reason animated movies look so realistic.

```
  💡 Light Source
   \
    \  ← random ray
     \
      🟦 Surface → reflects → 👁️ Camera
     /
    /  ← another random ray
   /
  💡 (missed — not counted)
```

> [!TIP]
> **Real-World Fact:** Pixar's movie *Monsters University* (2013) was the **first animated film** to use full Monte Carlo ray tracing for all lighting and shading!

### 🌟 Why It Matters

- 🎥 Every Pixar and Disney animated film uses this
- 🎮 Video games like *Minecraft RTX* use it for real-time lighting
- 🏗️ Architectural software uses it to show how sunlight will move through a building

### 🎮 Try It Yourself (No Code Needed!)

Shine a flashlight at a mirror in a dark room. Notice how light bounces. Now imagine doing that for BILLIONS of light rays in every direction — that's why computers need Monte Carlo shortcuts!

### 📺 Watch & Learn
- 🔗 [**Pixar in a Box: Rendering** — Khan Academy](https://www.khanacademy.org/computing/pixar/rendering) *(free interactive course!)*
- 🔗 [How Pixar uses ray tracing to make movies look real](https://www.youtube.com/results?search_query=pixar+ray+tracing+rendering+how+animation+lighting+works)

---

## 🚁 Application 4 — Finding Lost People (Search and Rescue)

<img src="https://img.shields.io/badge/Industry-Emergency_Services-DC143C?style=flat-square" alt="Emergency Services"/>

### 🔍 The Real Problem

When someone goes missing in the wilderness or at sea, rescue teams have a huge area to search. They can't cover everything at once, so they need to search the most likely areas first.

### 🎲 How Monte Carlo Helps

Rescue teams enter information they know — where the person was last seen, weather conditions, ocean currents, the person's physical fitness. The computer then simulates **thousands of possible paths** the lost person or drifting boat might have taken. This creates a "heat map" showing where the person is most likely to be.

```
  🌊🌊🌊🌊🌊🌊🌊🌊🌊🌊
  🌊  ⬜⬜🟨🟨🟧🟧⬜  🌊
  🌊  ⬜🟨🟧🟥🟧🟨⬜  🌊   🟥 = Most likely here!
  🌊  🟨🟧🟥🟥🟥🟧🟨  🌊   🟧 = Likely
  🌊  ⬜🟨🟧🟧🟨⬜⬜  🌊   🟨 = Possible
  🌊🌊🌊🌊🌊🌊🌊🌊🌊🌊   ⬜ = Unlikely
```

> [!IMPORTANT]
> **True Story:** This exact method was used to find the wreckage of **Air France Flight 447** in the Atlantic Ocean in 2011 — after TWO YEARS of unsuccessful searching, Monte Carlo probability maps guided rescuers to the crash site within **one week**!

### 🌟 Why It Matters

- 🇨🇦 The Canadian and US Coast Guards use this (software called SAROPS) to find people lost at sea
- ✈️ It located Air France Flight 447 under 4 km of ocean
- ⏱️ It helps rescue teams save time — and save lives

### 🎮 Try It Yourself (No Code Needed!)

Play a game with a friend: have them hide a small object in a room. You get to ask 3 yes/no questions about its location. Based on the answers, draw a quick map of where it's most likely to be. This is the basic idea behind Monte Carlo search planning!

### 📺 Watch & Learn
- 🔗 [How statisticians found Air France Flight 447](https://www.youtube.com/results?search_query=how+statisticians+found+air+france+447+bayesian+search+probability)

---

## 💰 Application 5 — Finance and Stock Market

<img src="https://img.shields.io/badge/Industry-Banking_&_Finance-228B22?style=flat-square" alt="Finance"/>

### 🔍 The Real Problem

Banks and investors need to answer questions like: *"If I invest $1,000 in this stock, what might it be worth in 5 years?"* But stock prices are unpredictable — they go up and down in ways nobody can perfectly forecast.

### 🎲 How Monte Carlo Helps

Financial analysts simulate the stock's price path **thousands of times** into the future. Each simulation uses random daily changes based on how the stock has behaved historically. After 10,000 simulations:

- They can say: *"There's a 90% chance your $1,000 will be worth between $800 and $2,500 in 5 years"*
- They can also find the **worst-case scenario** and the **best-case scenario**

```
  $$$  |          Simulation 1  📈 /$2,500
       |        /
       |      /    Simulation 2  📊 $1,800
  $$$  |    /   /
       |  / / /    Simulation 3  📉 $800
       | //
  $$$  |/  ← Start: $1,000
       |________________________
       Today              5 Years
```

> [!TIP]
> **Real-World Fact:** Banks are **legally required** by regulators to run Monte Carlo simulations every single day to prove they can survive a financial crisis!

### 🌟 Why It Matters

- 🏦 Banks use this daily to manage **billions of dollars** of risk
- 🛡️ Insurance companies use it to decide how much to charge for policies
- 👴 Retirement planners use it to check if your savings will last

### 🎮 Try It Yourself (No Code Needed!)

Start with $100 in play money. Flip a coin each "month":
- 🪙 Heads = your money goes up 10%
- 🪙 Tails = your money goes down 5%

Track your balance for 12 "months." Do this 5 times and compare the 5 different outcomes. Notice how the same starting point leads to very different results — that's exactly what banks simulate!

### 📺 Watch & Learn
- 🔗 [Monte Carlo Simulation for Finance Explained](https://www.youtube.com/results?search_query=monte+carlo+simulation+stock+market+finance+explained+simple+beginner)

---

## 👥 Application 6 — Estimating Crowd Sizes

<img src="https://img.shields.io/badge/Industry-Event_Management-FF8C00?style=flat-square" alt="Event Management"/>

### 🔍 The Real Problem

How do you count the number of people at a huge concert, protest, or sports event? You can't count every single person!

### 🎲 How Monte Carlo Helps

1. 📸 Take an aerial photo of the crowd
2. 📐 Divide the photo into a grid
3. 🎲 **Randomly select** 20–30 grid squares (this is the Monte Carlo part!)
4. 🔢 Carefully count the people in each selected square
5. ✖️ Calculate the average per square and multiply by the total number of squares

```
  ┌───┬───┬───┬───┬───┐
  │   │ ✅│   │   │   │  ✅ = Randomly selected squares
  ├───┼───┼───┼───┼───┤      (count people here)
  │   │   │   │ ✅│   │
  ├───┼───┼───┼───┼───┤  Average per square × Total squares
  │ ✅│   │   │   │   │  = Crowd estimate!
  ├───┼───┼───┼───┼───┤
  │   │   │ ✅│   │   │
  └───┴───┴───┴───┴───┘
```

### 🌟 Why It Matters

- 📰 News organizations use this to report crowd sizes at political events
- 🏟️ Event planners use it for safety — too many people in a space is dangerous
- 🌳 City planners use it to estimate how many people use public parks

### 🎮 Try It Yourself (No Code Needed!)

Next time you see a jar of candies 🍬, estimate the total: count the candies you can see on one "face" of the jar, then multiply by how many layers deep you think the jar is. You're using sampling to estimate a total — the Monte Carlo way!

### 📺 Watch & Learn
- 🔗 [How Do You Count a Crowd?](https://www.youtube.com/results?search_query=how+do+you+count+a+crowd+estimation+sampling+method)

---

## 💊 Application 7 — Medicine and Drug Testing

<img src="https://img.shields.io/badge/Industry-Medicine_&_Pharma-00CED1?style=flat-square" alt="Medicine"/>

### 🔍 The Real Problem

Before a new medicine can be given to patients, scientists need to know: *"Will this drug work? Will it cause side effects?"* Testing on millions of people is impossible, expensive, and would take decades.

### 🎲 How Monte Carlo Helps

Scientists build a computer model of how the drug interacts with the human body. They then simulate **thousands of virtual patients** with slightly different ages, weights, genetics, and health conditions. By running these simulations, they can predict:

- ✅ What percentage of patients will get better
- ⚠️ What side effects might occur
- 💉 What dosage works best for different age groups

> [!IMPORTANT]
> **True Story:** Monte Carlo simulations helped speed up **COVID-19 vaccine development** by simulating clinical trial outcomes before recruiting real patients — saving months of precious time during a global pandemic!

### 🌟 Why It Matters

- 🔬 This is used during early stages of drug development, **before** testing on real humans
- 🦠 It helped speed up COVID-19 vaccine development
- 💵 It reduces the cost and time of bringing life-saving medicines to market

### 🎮 Try It Yourself (No Code Needed!)

Imagine testing a "study technique" (your "drug") on your classmates. Not everyone studies the same way or has the same background. Roll a die for each imaginary student:
- 🎲 1–2 = the technique didn't help ❌
- 🎲 3–5 = it helped a little ✅
- 🎲 6 = it helped a lot! 🌟

Run this for 30 "students" and calculate your success rate.

### 📺 Watch & Learn
- 🔗 [Monte Carlo Simulation in Drug Development](https://www.youtube.com/results?search_query=monte+carlo+simulation+clinical+trial+drug+testing+pharmaceutical)

---

## 🚗 Application 8 — Traffic and City Planning

<img src="https://img.shields.io/badge/Industry-Urban_Engineering-696969?style=flat-square" alt="Urban Engineering"/>

### 🔍 The Real Problem

A city wants to add a new traffic light at a busy intersection. But will it actually reduce traffic jams, or will it make things worse by stopping the flow on the main road?

### 🎲 How Monte Carlo Helps

Traffic engineers simulate thousands of random "traffic days" — each day has a random number of cars, random arrival times, random pedestrians, and random accidents. They run the simulation twice:
1. ❌ **Without** the new traffic light
2. ✅ **With** the new traffic light

By comparing average travel times across thousands of simulated days, they can predict whether the light will help or hurt.

> [!TIP]
> **Real-World Fact:** Google Maps uses simulation-based traffic prediction combining data from millions of phones to estimate your arrival time — and it's accurate within minutes!

### 🌟 Why It Matters

- 🏙️ Cities use this before spending millions on new roads or transit systems
- 🗺️ Google Maps and Waze use similar simulations to suggest the fastest route
- ✈️ Airport designers use it to reduce delays at runways and terminals

### 🎮 Try It Yourself (No Code Needed!)

Time your walk through a hallway at school during class change. ⏱️ Do it 10 times and note how it varies. Now imagine the school adds a "one-way rule" for that hallway — how might it change? This is the thinking behind traffic simulation.

### 📺 Watch & Learn
- 🔗 [Traffic Simulation and City Planning](https://www.youtube.com/results?search_query=traffic+simulation+city+planning+how+it+works+Monte+Carlo)

---

## 🌍 Application 9 — Climate Change and Environmental Science

<img src="https://img.shields.io/badge/Industry-Environmental_Science-2E8B57?style=flat-square" alt="Environmental Science"/>

### 🔍 The Real Problem

Scientists want to predict what Earth's climate will look like in 50 or 100 years. But the climate depends on thousands of factors — carbon emissions, ocean currents, volcanic eruptions, deforestation, cloud cover — and we can't predict any of them perfectly.

### 🎲 How Monte Carlo Helps

Climate scientists run their models **thousands of times** with slightly different assumptions:
- 🏭 What if emissions go up 2% per year? What about 5%?
- 🌋 What if a major volcano erupts in 2040?
- 🌊 What if ocean currents shift?

Each simulation gives a different future. By looking at all of them together, scientists can say things like: *"In 95% of our simulations, global temperature rises by at least 1.5 degrees Celsius by 2050."*

```
  🌡️ Temperature
       |
  +3°C |                    ╱ Worst case 🔴
       |                 ╱╱
  +2°C |              ╱╱╱
       |           ╱╱╱╱    Most likely 🟡
  +1°C |        ╱╱╱╱╱
       |     ╱╱╱╱╱╱╱       Best case 🟢
   0°C |╱╱╱╱╱╱╱╱
       |________________________
       2025              2100
```

> [!IMPORTANT]
> **True Story:** The United Nations' IPCC reports — which guide **global climate policy** for every country on Earth — are built on thousands of Monte Carlo climate simulations!

### 🌟 Why It Matters

- 🇺🇳 The United Nations uses Monte Carlo climate models to set global policy
- 🌊 Governments use them to plan for flooding, droughts, and extreme weather
- 🌲 Scientists use them to study how protecting forests affects the future

### 🎮 Try It Yourself (No Code Needed!)

Track the high temperature in your city for 10 days. 🌡️ Now "predict" next week by randomly picking from your 10 recorded values for each day. Do this 5 times for 5 different "possible next weeks." You've just built a tiny climate model!

### 📺 Watch & Learn
- 🔗 [How Climate Models Work](https://www.youtube.com/results?search_query=how+climate+models+work+simulation+prediction+explained+simple)
- 🔗 [NASA Climate Kids: Climate Models](https://climatekids.nasa.gov/climate-model/)

---

## 🚀 Application 10 — Space Exploration and Rocket Science

<img src="https://img.shields.io/badge/Industry-Space_Exploration-000080?style=flat-square" alt="Space Exploration"/>

### 🔍 The Real Problem

When NASA or SpaceX launches a rocket, they need to land it on Mars — a target that is **225 million kilometers away**. Tiny errors in speed, angle, or timing can mean missing the planet entirely. And there are random factors they can't control: solar wind, micro-meteorites, and tiny fuel variations.

### 🎲 How Monte Carlo Helps

Engineers run **millions of simulated flights** before the real launch. Each simulation adds small random errors to:
- 🔥 Engine thrust (maybe 0.1% more or less than expected)
- 📐 Launch angle (off by a tiny fraction of a degree)
- ⛽ Fuel amount (slightly more or less than planned)

If the spacecraft lands safely on Mars in **99.9% of simulations**, the mission gets a green light. ✅

> [!IMPORTANT]
> **True Story:** NASA's Perseverance Rover had to survive **"7 Minutes of Terror"** — descending through Mars' atmosphere at 12,000 mph and landing safely. Engineers ran millions of Monte Carlo simulations beforehand to make sure the landing system worked in virtually every scenario!

### 🌟 Why It Matters

- 🔴 NASA's Mars rovers (Curiosity, Perseverance) were all tested this way
- 🚀 SpaceX uses it to land rocket boosters back on Earth
- 🛰️ Satellite companies use it to plan orbits

### 🎮 Try It Yourself (No Code Needed!)

Stand 3 metres from a waste bin. 🗑️ Try to throw a ball of paper into it 20 times. Record how many you make. Now try from 5 metres (harder — like aiming at a farther planet!). Your "hit rate" is your Monte Carlo success probability for that distance.

### 📺 Watch & Learn
- 🔗 [NASA: Perseverance Rover's 7 Minutes of Terror](https://www.youtube.com/results?search_query=NASA+perseverance+rover+7+minutes+of+terror+mars+landing)
- 🔗 [NASA Mars Exploration Interactive](https://eyes.nasa.gov/apps/mars2020/)

---

## 🧩 The Big Picture — What Connects All 10 Applications?

Every single application above follows the **same 3-step recipe** that you used in your red-card drawing project:

```
  ┌─────────────────────────────────────────────────┐
  │                                                 │
  │  Step 1: 🎯 Define the problem and the random   │
  │             factors involved                    │
  │                                                 │
  │  Step 2: 🔄 Run the experiment MANY times       │
  │             with random inputs                  │
  │                                                 │
  │  Step 3: 📊 Count the results and calculate     │
  │             probabilities                       │
  │                                                 │
  └─────────────────────────────────────────────────┘
```

> The only difference between your card experiment and NASA landing a rover on Mars is **scale** — they run millions of simulations on supercomputers, but the *idea* is identical to what you did with a deck of cards. 🃏➡️🚀

---

## 📋 Summary Table

| # | Application | Industry | What Gets Simulated | Emoji |
|:-:|------------|----------|-------------------|:-----:|
| 1 | Weather Forecasting | Meteorology | Thousands of possible tomorrows | ⛅ |
| 2 | Sports Predictions | Sports Analytics | Thousands of possible games | ⚽ |
| 3 | Movie & Game Graphics | Entertainment | Random light ray paths | 🎬 |
| 4 | Search and Rescue | Emergency Services | Thousands of possible drift paths | 🚁 |
| 5 | Stock Market & Finance | Banking | Thousands of possible price paths | 💰 |
| 6 | Crowd Size Estimation | Event Management | Random sample grid squares | 👥 |
| 7 | Drug Testing | Medicine | Thousands of virtual patients | 💊 |
| 8 | Traffic Planning | Urban Engineering | Thousands of random traffic days | 🚗 |
| 9 | Climate Prediction | Environmental Science | Thousands of possible futures | 🌍 |
| 10 | Rocket Launches | Space Exploration | Millions of simulated flights | 🚀 |

---

## 🎯 What's Next?

Now that you know WHERE Monte Carlo is used, here are some ideas to take your project further:

1. 🖼️ **Pick your favourite application** from the list and do a deeper research poster on it
2. 🎲 **Try the hands-on activities** — no computer needed, just dice, coins, and paper
3. 🔗 **Combine two applications** — for example, "How Monte Carlo helps predict both weather AND sports outcomes"
4. 💻 **When you're ready to learn coding**, your dad's Python notebook (`Pi_and_more_with_Monte_Carlo.ipynb`) is the perfect starting point — it shows you how to turn these dice-and-coin experiments into computer simulations that run thousands of trials in seconds!

---

## 📚 Additional Resources

| Resource | Link | What It Covers |
|----------|------|----------------|
| 🎥 Monte Carlo Intro Video | [A Simple Solution for Really Hard Problems](https://www.youtube.com/watch?v=slbZ-SLpIgg) | Best beginner intro |
| 🎥 Veritasium: Markov & Monte Carlo | [The Strange Math That Predicts Almost Anything](https://www.youtube.com/watch?v=KZeIEiBrT_w) | History + real-world applications |
| 🎥 Numberphile: Birthday Paradox | [Birthday Paradox](https://www.youtube.com/watch?v=a2ey9a70yY0) | Fun probability puzzle |
| 🎓 Khan Academy + Pixar | [Pixar in a Box: Rendering](https://www.khanacademy.org/computing/pixar/rendering) | Free course on how Pixar makes movies |
| 🌐 NASA Climate Kids | [Climate Models Explained](https://climatekids.nasa.gov/climate-model/) | Kid-friendly climate science |
| 🌐 NASA Mars Interactive | [Mars 2020 Landing Simulator](https://eyes.nasa.gov/apps/mars2020/) | Interactive Mars landing experience |
| 📖 Monte Carlo — Wikipedia | [Monte Carlo Method](https://en.wikipedia.org/wiki/Monte_Carlo_method) | Deep-dive reference |
| 📖 Monte Carlo — IBM | [What Is Monte Carlo Simulation?](https://www.ibm.com/think/topics/monte-carlo-simulation) | Clear business explanation |

---

<p align="center">
  <i>Created for Agnes Mary — from red cards to rocket science, it's all Monte Carlo!</i> 🃏🚀
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Made_with-❤️_by_Dad-red?style=for-the-badge" alt="Made with love by Dad"/>
</p>
