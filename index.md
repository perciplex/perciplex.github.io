## What is Perciplex?

We're a group of technical consultants and makers of [Reality as a Service](https://raas.perciplex.com). 

### What is Reality as a Service?

Reality as a Service or RaaS is a platform we built for trying code written for OpenAI Gym envoirnments on real robots. We built a fleet of pendulum robots that anyone can run your controller on.

```python
import gym
import gym_raas

env = gym.make('raaspendulum-v0')
env.reset()

for _ in range(1000):
 env.render()
 env.step(your_controller.get_action()) # take a random action

env.close()
```

### Who are you?
<div float="left">
 <img src="max_circle.png" alt="Max" width="120px" height="120px"></img>
 <img src="declan_circle.png" alt="Declan" width="120px" height="120px"></img>
 <img src="ben_circle.png" alt="Bax" width="120px" height="120px"></img>
 <img src="phil_circle.png" alt="Pax" width="120px" height="120px"></img>
 <figure>
    <img src="max_circle.png" height="120" width="120">
    <figcaption>Your label goes here</figcaption>
</figure>
</div>

### Support or Contact
Send us an email at [team@perciplex.com](mailto:team@perciplex.com)
