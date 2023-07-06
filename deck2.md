<!-- ICEBREAKER: Something going well, something going less well... -->

<!-- .slide: data-background="./assets/imgs/walking.gif" -->
## Project execution

Lean and Agile

Notes:

- So you have your project charters, your objectives, your stakeholders, your risks, your scope
- How do you execute it?
- How do you ensure you deliver what you intended to deliver?
- How do you adapt if things don't go to plan? (And they will!)

--

### Lean

> lean (`/li:n/`), *adjective*
>
> having no superfluous fat
>
> e.g. "Ruth had a lean, muscular body"
>
> - Slim, slender, healthy
> - (Of meat) not fatty
> - Not in excess

Notes:

- What does Lean mean?

--

#### A brief history of Lean

<div style="display: flex; flex-direction: row; justify-content: space-around; align-items: center;">
  <img src="https://upload.wikimedia.org/wikipedia/commons/1/12/1925_Ford_Model_T_touring.jpg" width="40%">
  <img src="https://upload.wikimedia.org/wikipedia/commons/7/71/1936_Toyoda_Model_AA_03.jpg" width="40%">
</div>

Notes:

- Lean (as a project/product development philosophy) was actually born in the manufacturing industry, at Toyota, in the 1930s
- Model T produced by Ford from 1908 to 1927 and is generally regarded as the first affordable and mass-produced car
- The Toyota AA was the first car Toyota produced in 1936

--

With the Ford T

- Started with the perceived 'perfect' product
- Strived to add value to the customer by standardizing the production and removing cost from the manufacturing process
- Large batches and economies of scale

Notes:

- This is a high risk strategy, as you are assuming you know what the customer wants
- It turned out well for Ford, but it could have gone the other way
- 'Any colour as long as it's black'

--

With the Toyota AA

- Seek perfection and **maximize value** to the customer
- **Remove waste** from the manufacturing process (e.g. overproduction, waiting, unnecessary transport, over-processing, excess inventory, defects)
- Produce in small batches for a more efficient pipeline (**flow**)

Notes:

- Took a different approach, by focusing on the customer and removing waste
- Did not assume they knew what the customer wanted, so tentatively produced in small batches, awaiting customers demand
- They were able to do so economically by removing waste from the manufacturing process (not doing anything unnecessary)

--

#### Waste

<img src="https://kanbanize.com/wp-content/uploads/website-images/kanban-resources/muda-mura-muri.png" width="70%">

Waste = anything that does not add value to the customer/project (does not contribute towards the SMART objectives)

Notes:

- The core premise behind Lean is to maximize value and to do so you need to eliminate waste
- Toyota identifies three types of waste
  - Muri (overburden) - machines and people can not work beyond their capacity
  - Muda (wastefulness) - activities that do not add value
  - Mura (unevenness) - e.g. having to crunch just before a deadline to meet the deadline (leads to a loss in quality)

--

#### Lean house

![Diagram of the Lean house.](./assets/imgs/Screenshot%20from%202023-06-20%2008-08-29.png)

Notes:

- What is the Lean house? A visualization of the principles of Lean
  - As the base you have Heijunka and Kaizen
  - Then you have the two pillars of JiT and Jidoka
  - Supporting the goal of quality, low cost and shortest lead time (time taken to complete a process)

--

#### Just-in-case (push) vs just-in-time (pull)

Notes:

- Toyota introduced a new paradigm in manufacturing: Just-in-time (JiT)

--

Just-in-case (push): make all we can just in case

- Production approximation
- Large batches
- High inventory
- Management by fire fighting

Notes:

- The traditional approach to manufacturing is to produce as much as possible, as quickly as possible, to benefit from economies of scale
- This is Just-in-case (push)
- You are having to make assumptions about what the customer wants, and you are having to store the inventory somewhere
- you make lots of approximations and that always carries risk

--

Just-in-time (pull): make only what is needed when it is needed

- Production to demand
- Small batches
- Low inventory
- Management by sight

Notes:

- JiT does not make any assumptions about what the customer wants
- It is triggered by the customer demand
- This may seem like a slower process, but it is actually more efficient
- You end up with something you know the customer wants, and you have not wasted time and resources on something they don't want

--

#### Jidoka (intelligent automation)

Ability to self-monitor and self-correct

![Cartoon showing the evolution of Jidoka. Going from a simple manufacturing process to a sophisticated automated process.](https://www.lean.org/wp-content/uploads/2020/07/jidoka.gif)

Notes:

- Anecdote of the technician in the packing factory
- A famous packaging company had this issue in their packing process where due to a fault in the line, some boxes were not filled. They needed a way to prevent those boxes from making their way to the end of the line to be loaded into trucks.
- They spent millions hiring an engineering consultancy to look into the problem and how the fix could be automated using extra sensors
- In the meantime they asked someone on the factory floor to sit by the line and manually check and remove empty boxes
- While the engineering consultancy were testing prototypes and running late on the project, the person on the factory floor, out of sheer boredom, figured out: if he just put the fan he was using to cool himself facing the line, the lighter empty boxes would simply be blown off while the heavier filled boxes stayed.
- Moral of the story is to allow for inelegant intervention from everyone! Trust and respect the workforce!

--

#### 7 principles of Lean manufacturing

1. Eliminate waste
2. Amplify learning
3. To defer commitment
4. Deliver fast
5. Empower the team
6. Build integrity in
7. See the whole

Notes:

- Defer commitment (JiT)
- **The concept of learning and focus on upskilling the team is key**
- How are the Lean principles relevant to us?
- Do you see anything here that would be exclusive to manufacturing? No!

--

#### Lean manufacturing in action: Kanban

![Picture of a fast food restaurant order regulator.](https://foodtank.com/wp-content/uploads/2015/08/fastfood.jpg)

Notes:

- A place that you may know that embraces Lean manufacturing is fast food restaurants
- While I don't advocate for them, they do a good job of scaling and making food to order while minimizing waste

--

![Diagram of JIT for fast food restaurants.](./assets/imgs/Screenshot%20from%202023-06-20%2009-19-01.png)
![Diagram of JIT for software development products.](assets/imgs/Screenshot%20from%202023-06-20%2009-19-09.png)

Notes:

- On the left, diagram of JiT in a burger fast food
  - As orders come in, burgers removed from regulator (is the device that holds the burgers)
  - Food is **pulled** from the burger regulator when a customer asks for it
  - That notifies the kitchen that they need to start work once more
  - Replenished on-demand (JIT) by the kitchen
- Not made to a forecast and pushed to a customer (who may not want a burger) as that would be wasteful
- This same technique is used in software development, where a feature is requested by a customer/user and that **triggers** the programmers to start the work (responding to the customers needs not anticipating them)
- More recently these techniques are used in fashion where clothes are made in small batches

--

#### Minimum viable product (MVP)

![Breakdown of the meaning of MVP.](./assets/imgs/Screenshot%20from%202023-06-20%2009-34-32.png)

Notes:

- Producing an MVP is a good way to embrace the Lean philosophy
- Let's break it down...

--

![Cartoon strip showing benefit of a skateboard vs. a set of car wheels.](assets/imgs/Screenshot%20from%202023-06-20%2009-34-40.png)

Notes:

- This picture does such a good job of showing the effectiveness of building an MPV
- The idea is that it is more valuable to provide a full useful thing rather than parts of a more complex thing
- e.g. you want to provide mobility but don't have the capacity to build a car, build a skateboard. Over time, you will be able to deliver a car!

--

Lean development

![The cycle of Lean development. Going from process mapping to set-based design to MVP delivery to rinse and repeat.](assets/imgs/Screenshot%20from%202023-06-20%2009-40-22.png)

Notes:

- [BREAK]

--

### Waterfall

![Naive Waterfall diagram](assets/imgs/Screenshot%20from%202023-06-30%2013-33-15.png)

Notes:

- Naive waterfall is a linear process
- You go from one stage to the next, and it doesn't account for feedback or iteration (it assumes you got it right the first time)
- Doesn't take into consideration the view of your end user (the person to whom you are attempting to deliver value)
- In can be effective if you know exactly what you're doing but more often than not, it is not the case

--

In practice, becomes complicated...

![Complex Waterfall diagram](assets/imgs/Screenshot%20from%202023-06-30%2013-34-35.png)

Notes:

- What ends up happening the process becomes significantly more complicated to avoid ending up with a product that is not what the end user wants
- Nobody ever thought naive waterfall was a good idea (even its creator, Winston Royce, said it was bad)
- Useful for illustrating the value of Agile

--

### Agile

> agile (`/ˈadʒʌɪl/`), *adjective*
>
> able to move quickly and easily
>
> e.g. "Ruth was as agile as a cat"
>
> - nimble, supple
> - acrobatic, dexterous, graceful

Notes:

- Moving, **adapting**, responding to change

--

#### Agile approach

```bash
Stakeholder -> Product owner -> Development team -> User
                      ^                               |
                      |                               |
                      ---------------------------------
```

Notes:

- The approach is built around the idea of a product owner who is the voice of the user
- Iteration is built into the process
- So the stakeholder and user feed information regularly to the product owner who then shares the direction with the dev team
- Fragments or MVPs are delivered regularly, each iterating on one another
- Mitigates one of the biggest risks in delivering a project/product, making something that nobody wants!

--

#### Paradigm shift

| Naive Waterfall | Agile |
| --------- | ----- |
| Plan driven    | Value driven |
| fixed scope, estimate cost/time | fixed cost/time, estimate scope |
| sequential | iterative |
| top-down | bottom-up |

Decreases the cost, time and quality risk!

Notes:

- Fixed scope, assumes you got the perfect product from the start (Ford) - it is possible to be successful that way but higher risk
- Bottom-up from the end user (feedback from users)
- If cost and time a hard constraint, then scope must be varied and this is the one of the best ways to ensure you get the most value for your money/time
--

#### Agile manifesto

> - **Individuals and interactions** over processes and tools
> - **Working [solutions]** over comprehensive documentation
> - **Customer collaboration** over contract negotiation
> - **Responding to change** over following a plan

Notes:

- The manifesto was made by a few people sitting in a room in 2001 who were frustrated with the way status quo of software development
- This came about in software development, but now these principles are applied to all sorts of projects (fashion, content creation, construction, etc.)
- The manifesto states
  - Like in Lean we value people, instead of trying to remove them from the process with necessary automation (allow everyone to contribute and be creative, listen to everyone's suggestions)
  - Don't focus too much on writing documentation and reports
  - Collaborate with your end users
  - Be willing to change your original plan

--

#### Agile approaches

![Different Agile frameworks](https://codeit.us/storage/Ix25AhQpABMfNocjnRyCHFyywe6fwwRN42IwkPaz.png)

Notes:

- Agile is a philosophy / state of mind
- Over the years' company have developed frameworks to help them formally be Agile
- Can be a little confusing

--

#### Scrum basics

Notes:

- The most popular/mainstream framework for being Agile is Scrum
- It is a little confusing to begin with, cause there is quite a lot of funny terminology, but it is actually quite simple

--

##### User stories

- **User stories** allow you to capture scope in a way that relates to your end user
- You add a priority, estimation of size (how long it'll take person/hours), Definition of Done (DoD), and acceptance criteria

> As a [type of user], I want to [perform some task] so that I can [achieve some goal].

Notes:

- The main idea with being Agile is that you are able to respond to change coming from your end user
- So you need to have a way of capturing what they want
- This is where user stories come in...
- Estimation of size is usually done by consensus of the team (e.g. 1-5 discussion)
- The Definition of Done sets the overall standard of completion for all user stories in a project or sprint, while Acceptance Criteria specify the specific conditions that must be met for each individual user story to be considered successfully implemented

--

##### Backlog

- **Product backlog** is a list of **user stories**
- Product owner takes inputs from end-users, stakeholders and the team to build and maintain the backlog
- Sprint backlog is a subset of the product backlog that the team commits to delivering in a **sprint**

Notes:

- The product backlog is a list of all the user stories that you want to deliver (these have been validated by the stakeholders and end users)

--

##### Sprint

- **Sprint** is a time-boxed period of development (usually 2 weeks)
- Idea is to deliver a working product/MVP at the end of each sprint and gather feedback from the end user
- Use this feedback to inform the next sprint

Notes:

- Essentially, build something useful (even if it is not exactly what you want to build) in two weeks, get feedback on that, and see where to go from there
- I think it helps with the mental strength of pursuing a project, it is much easier to commit to something for two weeks than it is to commit to something for 6 months + more satisfying to see progress

--

##### Daily stand-up

- **Daily stand-up** is a short meeting (~15 minutes) where the team discusses what they did yesterday, what they are doing today and any blockers
- Promotes transparency and cross-collaboration

--

![Stages of Scrum](https://scrumorg-website-prod.s3.amazonaws.com/drupal/inline-images/2023-02/screenshot_2023-02-14_at_8.36.08_am.png)

Notes:

- User stories are gathered to form backlog
- Team democratically selects how much they can commit to by pulling from the backlog into the sprint backlog
- Sprint commences
- Daily stand-up to assign work and measure progress
- At end of sprint deliver new iteration, review, gather feedback (to feed the product backlog) and retrospective (to improve the process)

--

What does this look like?

You can do it any way you want? Pieces of paper, sticky notes, whiteboard...

[Feature & bug tracking demo](https://trello.com/invite/b/0G4E8Z4n/ATTIcbeef1d5237f01e13170865eca614339CB12D420/featurebug-tracking-demo)

Notes:

- Suggest using a Kanban board
- Let's make this a little more concrete...
- [Inspired by Pura team's persona](https://docs.google.com/presentation/d/1_zO5rCeqFXWZabfViOyaNd2_u8ImNmaj_d6B662yRco/edit#slide=id.g242c09ee597_0_115)

--

### Reconciling Agile and Lean

- Mutually beneficial
- Lean is about maximizing value to the customer (only delivering what is needed) think bike not car wheel
- Agile is about adapting, listening to end users (customers) and being willing to adapt the output

---

## Key takeaways

- Make sure what you are doing is useful **by talking to people**
- Fail fast, fail cheap
- Don't be afraid to change your mind
- Better to have something that works than something that is perfect (MVP)

---

Some tools to help you along the way...

- [Figma](https://www.figma.com/) - Digital design and prototyping tool
- [diagrams.net](https://app.diagrams.net/) - Diagramming tool
- [Trello](https://trello.com/) - Collaborative Kanban boards
- [Google domains](https://domains.google.com/) - Company domain names
- [Weebly](https://www.weebly.com/) - Drag-n-drop website builder

Notes:

- If I have time, do a short demo of Figma...
