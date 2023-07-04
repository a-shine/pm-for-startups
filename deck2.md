<!-- ICEBREAKER: something going well, something going less well... -->

<!-- .slide: data-background="./assets/imgs/walking.gif" -->
## Project execution

Lean and Agile

Notes:

- So you have your project charters, your objectives, your stakeholders, your risks, your scope
- How do you execute it?
- How do you ensure you deliver what you intended to deliver?
- How do you adapt if things don't go to plan?

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

--

#### A brief history of Lean

<div style="display: flex; flex-direction: row; justify-content: space-around; align-items: center;">
  <img src="https://upload.wikimedia.org/wikipedia/commons/1/12/1925_Ford_Model_T_touring.jpg" width="40%">
  <img src="https://upload.wikimedia.org/wikipedia/commons/7/71/1936_Toyoda_Model_AA_03.jpg" width="40%">
</div>

Notes:

- Model T produced by Ford from 1908 to 1927 and is generally regarded as the first affordable and mass-produced car
- The Toyota AA was the first car Toyota produced in 1936

--

With the Ford T

- Started with the perceived 'perfect' product
- Strived to add value to the customer by standardizing the production and removing cost from the manufacturing process
- Large batches and economies of scale

--

With the Toyota AA

- Seek perfection and **maximize value** to the customer
- Remove waste from the manufacturing process (e.g. overproduction, waiting, unnecessary transport, over-processing, excess inventory, unnecessary motion, defects)
- Produce in small batches for a more efficient pipeline (**flow**)

--

#### Waste

<img src="https://kanbanize.com/wp-content/uploads/website-images/kanban-resources/muda-mura-muri.png" width="70%">

Waste = anything that does not add value to the customer/project (does not contribute towards the SMART objectives)

Notes:

- The core premise behind Lean is to eliminate waste
- Muri (overburden) - machines and people can not work beyond their capacity
- Muda (wastefulness) - activities that do not add value
- Mura (unevenness) - e.g. having to crunch just before a deadline to meet the deadline

--

#### Toyota Eliminating waste

1. Transport in excess of what is required
2. Inventory in excess of what is required
3. Motion between processes
4. Waiting got processes to finish or people/machines that are unavailable
5. Over processing beyond what is required
6. Overproduction ahead of demand
7. Defects and parsing poor quality down the supply chain
8. Skills not seeking expertise and creativity

--

#### Lean house

![Diagram of the Lean house.](./assets/imgs/Screenshot%20from%202023-06-20%2008-08-29.png)

--

#### Just-in-case (push) vs just-in-time (pull)

--

Just-in-case (push): make all we can just in case

- Production approximation
- Large batches
- High inventory
- Management by fire fighting

--

Just-in-time (pull): make only what is needed when it is needed

- Production to demand
- Small batches
- Low inventory
- Management by sight

--

#### Jidoka (intelligent automation)

Ability to self-monitor and self-correct

![Cartoon showing the evolution of Jidoka. Going from a simple manufacturing process to a sophisticated automated process.](https://www.lean.org/wp-content/uploads/2020/07/jidoka.gif)

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

- So how are the Lean principles relevant to us?
- Do you see anything here that would be exclusive to manufacturing?

--

#### Lean manufacturing in action: Kanban

![Picture of a fast food restaurant order regulator.](https://foodtank.com/wp-content/uploads/2015/08/fastfood.jpg)

Notes:

- As orders come in, burgers removed from regulator
- Replenished on-demand (JIT) by the kitchen
- Not made to a forecast and pushed to a customer (who may not want a burger) as that would be wasteful

--

![Diagram of JIT for fast food restaurants.](./assets/imgs/Screenshot%20from%202023-06-20%2009-19-01.png)
![Diagram of JIT for software development products.](assets/imgs/Screenshot%20from%202023-06-20%2009-19-09.png)

--

#### Minimum viable product (MVP)

![Breakdown of the meaning of MVP.](./assets/imgs/Screenshot%20from%202023-06-20%2009-34-32.png)

--

![Cartoon strip showing benefit of a skateboard vs. a set of car wheels.](assets/imgs/Screenshot%20from%202023-06-20%2009-34-40.png)

Notes:

- The idea is that it is more valuable to provide a full useful thing rather than parts of a more complex thing
- e.g. you want to provide mobility but don't have the capacity to build a car, so you build a skateboard

--

Lean development

![The cycle of Lean development. Going from process mapping to set-based design to MVP delivery to rinse and repeat.](assets/imgs/Screenshot%20from%202023-06-20%2009-40-22.png)

--

### Waterfall

![](assets/imgs/Screenshot%20from%202023-06-30%2013-33-15.png)

Notes:

- Naive waterfall is a linear process
- You go from one stage to the next, and it doesn't account for feedback or iteration (it assumes you got it right the first time)
- Doesn't take into consideration the view of your end user (the person to whom you are attempting to deliver value)

--

In practice, becomes complicated...

![](assets/imgs/Screenshot%20from%202023-06-30%2013-34-35.png)

Notes:

- What ends up happening the process becomes significantly more complicated to avoid ending up with a product that is not what the end user wants
- Nobody ever thought naive waterfall was a good idea (even its creator, Winston Royce, said it was a bad idea)
- Often used as a benchmark for other processes

--

### Agile

> agile (`/ˈadʒʌɪl/`), *adjective*
>
> able to move quickly and easily
>
> e.g. "Ruth was as agile as a cat"
>
> - nimble, supple
> - acrobatic dexterous, graceful

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

--

<!-- md 2 col table -->

#### Paradigm shift

| Tradition/naive | Agile |
| --------- | ----- |
| Plan driven    | Value driven |
| fixed scope, estimate cost/time | fixed cost/time, estimate scope |
| sequential | iterative |
| top-down | bottom-up |

Decreases the cost, time and quality risk!

--

#### Agile manifesto

> - **Individuals and interactions** over processes and tools
> - **Working [solutions]** over comprehensive documentation
> - **Customer collaboration** over contract negotiation
> - **Responding to change** over following a plan
>
> That is, while there is value in the items on
> the right, we value the items on the left more.

Notes:

- This came about in software development, but now these principles are applied to all sorts of projects (fashion, content creation, construction, etc.)

--

#### Agile approaches

![](https://codeit.us/storage/Ix25AhQpABMfNocjnRyCHFyywe6fwwRN42IwkPaz.png)

Notes:

- Agile is a philosophy / state of mind
- Over the years' company have developed frameworks to help them formally be agile

--

#### Scrum basics

Product backlog (built and maintained by the product owner)
filled with user stories
epics (group of related user stories)
allows you to capture scope in a way that relates to your end user

to a user story you add a priotity, estimation of size (how long it'll take person/hours), definition of done

product ownwer - input from end-users, stakeholders, team... (maintains and builds the backlog)

--

![](https://scrumorg-website-prod.s3.amazonaws.com/drupal/inline-images/2023-02/screenshot_2023-02-14_at_8.36.08_am.png)

Notes:

- User stories are gathered to form backlog
- team democratically select how much they can commit to by pulling from the backlog into the srint backlog (they works together to estimate user story size while the product pwner assignes priority and definiton of done)
- sprint comences (usualy over 2 weeks)
  - daily standup by scrum master to assign work and measure progress
- at end of sprint deliver new iteration, review, gather feedback and retrospective

--

What dows this look like?

You can do it any way you want? Pieces of paper, sticky notes, whiteboard...
Suggest using a Kanban board

<!-- TODO: show demo kanban board -->

--

### Reconciling Agile and Lean

- Mutually beneficial
- lean is about maximising value to the customer (only delivering what is needed and working) think bike not car wheel
- agile is about adapting, listening to end users (customers) and being willing to adapt the output

you can do both!

---

## Key takeaways

- make sure what you are doing is useful by talking to people

---

Some tools to help you along the way...

- Figma
- diagrams.net
- Trello
- Google domains (for domain names)
- Weebly (for websites) (alternatively for those that want to code, GitHub pages)

Make sure to version control your work!
