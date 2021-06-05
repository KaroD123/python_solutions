# Prework review

Hi Karolin 🙋🏻‍♀️!! I am writing to give you some feedback on your prework! 🚀

### 1. Snail-and-Well

The part of the exercise you have done is perfect Karoline, good job. But... what happened to the last exercises? Was there something you didn't understand? If so, tell me and we'll go through it with you.


### 2. Duel-of-Sorcerers

The first part of this exercise it is perfect, but... What happened with the bonus? 

The first step that we should do in this exercise is extract the values (from the dictionary) of each power for each sorceress. For do this we could code: 

```python
#create two new lists where we append each value for a given value
gandalf_power = []
saruman_power = []

# then extract the values from the dictionary
for g in gandalf:
    gandalf_power.append(POWER[g]) # we get a list with each value of a given power for gandalf

for s in saruman:
    saruman_power.append(POWER[s])

# then, you should iterate between this two new list and compare each value in gandalf_power and saruman_power. 

for spell in range(spells):
    
    if gandalf_power[spell] > saruman_power[spell]:
            # to ensure that one of the Sorcerers win 3 duels it is necessaty to reset the counter 
            gandalf_wins += 1 🚨
            saruman_wins = 0 🚨
            if gandalf_wins == 3:
                print(f'Gandalf has won {gandalf_wins} clashes in a row, he is the winner of the battle!\n')
                break
            else:
                print(f"Gandalf wins this clash. It is the {gandalf_wins} victory in a row!\nSaruman's wins are reset to 0.\n")
    ... # and the other condition
```

Although they are not mandatory, it is important that we do them because they will help us to create more complex code and can be a challenge from which we will learn a lot.

### 3. Bus

Good job!!!!

Only, as a detail, in python yoy have the `mean` and `stedev` functions that give us the mean and standard deviations of a given list of numbers. We only need to import `statistics` library. Here is an example in case you find it usefull:

```python
import statistics
numbers = [1, 3, 4, 5, 7, 9, 2]
  
x = statistics.mean(numbers)
  
print("Mean is :", x)
```
### 4. Robin-Hood

Really really good job in this challenge Karolin!!! This exercise was quite difficult and you pulled it off super well! Congratulations!! 🚀

### 5. Temperature-Processor

Suuuuperrrr!!!! 💪 It is perfectttttt

### 6. Rock–Paper–Scissors

I am blown away! What a great job you did Karolin! Keep up the good work, you'll do great!

- The bonus exercise was similar to rock, paper, scissors, the only thing we should do is add two more possible options.


Well Karolin, overall you did a good job, however in most cases you didn't try the bonus part. If these exercises were difficult for you, tell me, we could try to explain it in more detail. 
Still, great job Karolin!!!! You are on the data analysis rocket! 🚀
