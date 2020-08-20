# What is Perciplex?

We're a group of technical consultants and makers of [Reality as a Service](https://raas.perciplex.com). 

## What is Reality as a Service?

**Reality as a Service** or **RaaS** is a platform we built for testing OpenAI Gym controllers on real robots. We built a fleet of pendulum robots that you can run your controller on for free. 

If you already have a `Pendulum-v0` controller, it's this easy to try RaaS:
```python
import gym
import gym_raas

env = gym.make('RaasPendulum-v0')
env.reset()

for _ in range(1000):
 env.render()
 env.step(<<YOUR CONTROLLER HERE>>) # take a random action

env.close()
```
Head over to [raas.perciplex.com](https://raas.perciplex.com) to access _reality_. Check out the docs at [here](https://perciplex.github.io/raas/).

## Who are you?
<table style="border:none;align:center;">
 <tr>
  <td><img src="max_circle.png" alt="Max" width="100px" height="100px"></td>
  <td><img src="declan_circle.png" alt="Declan" width="100px" height="100px"></td>
  <td><img src="ben_circle.png" alt="Bax" width="100px" height="100px"></td>
  <td><img src="phil_circle.png" alt="Pax" width="100px" height="100px"></td>
 </tr>
 <tr>
  <td>Maximilian King</td>
  <td>Declan Oller</td>
  <td>Ben Wiener</td>
  <td>Philip Zucker</td>
 </tr>
</table>


## Support or Contact
Feel free to send us an email at [team@perciplex.com](mailto:team@perciplex.com).
