# Productivity and states of the world


We want to empirically show that a firm's productivity now depends on (1) technology and (2) a bet they made in the past regarding future potential states of the world. Firms position themselves at time t while thinking of t+s, and in t+s there is uncertainty about what the world is going to look like, AKA there are many potential future states of the world. Firms position themselves relative to these future states not just because of their likelihood, but because of each states' stochastic discount factor (~ marginal utility in that scenario). If the SDF is high, an extra unit of the production of that firm is very valuable.

Currently there is a model and now we want to find the empirics to back it up. There are 2 ways to show it:
1. Show that when the probability of future events change firms reallocate capital (we want to show that when the probability of X changes, capital react in a measurable way) (_forward looking behavior of firms_)
2. Show that when a shock hits, firms that were more exposed to that state of the world increased TFP (_"backward induction"_)
    - How do we measure exposure to states? _I would say it has to do with capital accumulation, but the type of capital we look at depends on the shock, and is something we will have to determine once we have the shock we want to look at. E. g with COVID, exposure to the shock was having RNAm tecnology._

**Ideal set-up**
1. Something changes the probability of an event, some firms react and others do not, 
2. The state is realized or not  so
    - Event is realized: those that positioned themselves have a TFP change
    - Event is not realized: those that positioned do not have a TFP change 


We have to find data (establishment/firm level) on sectors that look at the states of the world
- Which sectors are more forward looking

Places to look at:
- Energy: 
    - in energy literature dp they look at TFP and talk about states of the world?
    - ideally plant level data of their capital and production
    - ENERGY GENERATION IN US OR EUROPE MIGHT HAVE OPEN DATA AT THE PLANT LEVEL (ENERGY GENERATED AT WHAT PRICE?)
- Gas stations
- Bloomberg > Bloomberg terminals are available in Doriot & Tanoto Research & Learning Hubs only. In the Tanoto Research & Learning Hub, use the designated computer in the Financial & Research Data Circle (INSEAD SSO required).

## Which sectors are more forward looking

Google: what sectors depend more on future states of the world?

> Technology (especially Artificial Intelligence and Quantum Computing), Renewable Energy, Biotechnology, and Space Exploration are the sectors that depend most heavily on future states of the world. Because these industries rely on long-term R&D, unproven technologies, and evolving regulatory landscapes, their current valuation is almost entirely tied to scenarios that have not yet occurred.

<mark>**long-term R&D, unproven technologies, evolving regulatory landscapes**
- _Using the regulatory landscape could be good for having a clean identification strategy_

Industries with high competition and growth: https://www.mckinsey.com/mgi/our-research/capturing-the-next-big-arenas-of-competition-in-ten-charts
- They might be interesting as they concentrate a LOT of R&D 
    > " In the United States, about two-thirds of all R&D spending was allocated to arenas and arena-adjacent industries."

One firm carrying aggregate productivity gains: https://www.mckinsey.com/mgi/our-research/the-power-of-one-how-standout-firms-grow-national-productivity
- kd

## Plant-level data

**Encuesta Anual Manufacturera - Colombia (1977 - 2024)**
   - Used in Midrigan and Yi Xu (2014, AEA): "Finance and Misallocation: Evidence from Plant-Level Data"
  -  Está constituido por la totalidad de los establecimientos industriales que funcionan en el país y que son reconocidos como tal por la Clasificación Industrial Internacional Uniforme de todas las actividades económicas (CIIU) Revisión 4 Adaptada para Colombia.
  - Está conformada por los establecimientos que se definen como industriales y que funcionan en el país, según la CIIU Rev.4 A.C. éstos deben tener diez o más personas ocupadas o un valor de producción superior al estipulado anualmente. 

**ORBIS**
- Financial information for over 60,000 public companies and over 40 million private companies worldwide.
- <mark>Access will be discontinued on February 28, 2027

**International Data Access Network**
- Network between data centers in France (CASD), Germany, Netherlants, UK

**Bloomberg**
- I don't know what we have there, I have to go down to the terminal to see
- Part of the broader "commercial microdata": Dealscan, NL Analytics, CapitsalIQ, Datastream, Worldscope#


**World Bank Enterprise Survey**


## Roadmap

ChatGPT quotes
- Measured productivity can reflect how firms position their resources across possible futures, not merely how technologically efficient they are.
- The same investment may produce different amounts of output under different circumstances.[...] Without states of the world, there would be no distinction between capital that is productive today and capital that is valuable for another possible future.
- Increasing future disaster preparedness can mean giving up some productive opportunities in normal states.
- The firm can rationally fund a project of lower quality because it has an especially valuable state-contingent payoff.
- Suppose a firm has access to many projects ranked by quality. It funds the most attractive project first, then the next-best one, and so on. As the firm expands, the projects it adds tend to be less productive.
- When a particular type becomes more valuable, the firm can afford to fund lower-quality projects of that type. This produces the quality ladder.



Outstanding questions
- I do not fully understand the risk-neutral probability: I understand that it is like a weight, but what is it for? What is the interpretation of each risk neutral probability?
- You say "The model's date-0 state price is not automatically identical to an electricity spot price observed during a scarcity hour". Is this interpretation more appropriate?: supposing that the price of oil is very elastic to oil supply, in a state of the world (s) where the global supply of oil diminishes by 10% (-10mb/d) the price of oil would increase 1USD, so imagining that it used to be at 60USD/barrel, could we say that the state price in state s is 61USD?
- In the sentence: "the firm funds everyproject worth at least the rental rate of capitall", does this mean that the marginal project will be the one that is worth (gives money to the firm) the same as the marginal costo fo capital?
- I don't understand why a smaller (\eta\) leads to smaller funding elasticity. Also, what is \eta\?
- I do not fully understand the envelope theorem
- when the firm shifts toward poducing more in the disaster state, I do not understand why TFP does not increase in the non-disaster state given the quality gradient. The first projects to be defunded should be the projects that have the lowest quality and thus, their supressig effect on TFP must go away, right?
- I understand the mechanism of feedback in D10, but I don't know how we made the jump from that mechanism to the assumption or the prediction