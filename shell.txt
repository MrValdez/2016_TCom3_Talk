>>> print("Can you read this?")
Can you read this?
>>> import pytts
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
ImportError: No module named 'pytts'
>>> import pyttsx
>>> pyttsx.speak("Hello everyone. Can you hear and read this?")
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
AttributeError: 'module' object has no attribute 'speak'
>>> pyttsx.speak("Hello everyone. Can you hear and re
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
AttributeError: 'module' object has no attribute 'speak'
>>> a = pyttsx.init()
>>> a.speak("Hello everyone. Can you hear and read th
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
AttributeError: 'Engine' object has no attribute 'speak'
>>> dir(a)
['__class__', '__delattr__', '__dict__', '__dir__', '__doc__', '__eq__', '__format__', '__ge__', '__getattribute__', '__gt__', '__hash__', '__init__', '__le__', '__lt__', '__module__', '__ne__', '__new__', '__qualname__', '__reduce__', '__reduce_ex__', '__repr__', '__setattr__', '__sizeof__', '__str__', '__subclasshook__', '__weakref__', '_connects', '_debug', '_driverLoop', '_inLoop', '_notify', 'connect', 'disconnect', 'endLoop', 'getProperty', 'isBusy', 'iterate', 'proxy', 'runAndWait', 'say', 'setProperty', 'startLoop', 'stop']
>>> a.say("Hello everyone. Can you hear and read this?")
>>> a.runAndWait()
>>> a.say("Hello everyone. Can you hear and read this?")
>>> a.runAndWait()
>>> a.say("Good afternoon. I am the Doctor, Mister valdez.")
>>> a.runAndWait()
>>> a.say("I will be giving a beginner's guide to encyption.")
>>> a.runAndWait()
>>> a.say("Question: What is encryption?")
>>> a.say("Who was the one who answered earlier?")
>>> a.runAndWait()
>>> a.say("correct. to hide information")
>>> a.runAndWait()
>>> a.say("Let's imagine two people: alice and bob")
>>> a.runAndWait()
>>> a.say("Question: What is ASCII?")
>>> a.runAndWait()
>>> a.say("Correct.")
>>> a.runAndWait()
>>> a.say("What is the ASCII code for 'A'?")
>>> a.runAndWait()
>>> a.say("I also don't know")
>>> a.say("Good thing, I have a programming language in my hands")
>>> a.runAndWait()
>>> print(ord("A"))
65
>>> a.say("The ASCII code for A is {}".format(ord("A"))
... )
>>> a.runAndWait()
>>> a.say("For the simple example, let's say Alice wants to say A to Bob")
>>> a.runAndWait()
>>> a.say("That is normal")
>>> a.runAndWait()
>>> a.say("in this example, a bad guy changed Alice's message")
>>> a.runAndWait()
>>> a.say("Bob is unhappy now. :(")
>>> a.runAndWait()
>>> a.say("Just a check. Did I get the spelling right?")
>>> a.say("Oh well")
>>> a.runAndWait()
>>> a.say("I am a bad speller")
>>> a.runAndWait()
>>> a.say("Let's try to encrypt using a semetricalllyie encryption")
>>> a.runAndWait()
>>> a.say("This encryption is called the \"Caesar\" encryption")
>>> a.runAndWait()
>>> a.say("Question: What is a key?")
>>> a.runAndWait()
>>> a.say("Y'all only converted to Filipino")
>>> a.runAndWait()
>>> a.say("Question: What is a key?")
>>> a.runAndWait()
>>> a.say("Yes. it is a device or way to enter a locked door/message")
>>> a.runAndWait()
>>> a.say("In this example, our key is 16")
>>> a.say("We add 16 to our message. and we give to Bob")
>>> a.say("Bob will now decrypt the message using the key of 16")
>>> a.runAndWait()
>>> a.say("In this example, Bob got the correct message. Notice that the bad guy only see the number 80 and not the original message of 64")
>>> a.runAndWait()
>>> a.say("This is a simple example. But y'all can see the disadvantage of semetricall encryption")
>>> a.runAndWait()
>>> a.say("Question. what is the problem of this encryption?")
>>> a.runAndWait()
>>> a.say("Answer: The key is PUBLIC")
>>> a.runAndWait()
>>> a.say("A common fix to this is to send the key also. but how can you do that??")
>>> a.runAndWait()
>>> a.say("So, mathematicians invented assymetrical encryption")
>>> a.runAndWait()
>>> a.say("Question: What is public and private key?")
>>> a.runAndWait()
>>> a.say("Anyone?")
>>> a.runAndWait()
>>> a.say("But the question is: What is public and pr
>>> a.runAndWait()
>>> a.say("So, in this example, both Alice and Bob has public and private keys")
>>> a.runAndWait()
>>> a.say("Question. What are the numbers 3, 5, 7?")
>>> a.runAndWait()
>>> a.say("What are prime numbers?")
>>> a.runAndWait()
>>> a.say("In mathematics, prime keys are used in encryption")
>>> a.runAndWait()
>>> a.say("How to use it? Let's go back to the example of Alice sending the message 64 to Bob")
>>> a.runAndWait()
>>> a.say("Alice should multiply her number with her private and public key")
>>> a.runAndWait()
>>> a.say("What is 64 * 3? Its {}".format(64*3))
>>> a.runAndWait()
>>> a.say("192 multiplied by 5 (the private key) is:")
>>> a.runAndWait()
>>> 192*5
960
>>> a.say("The number 960 is sent over the network. To the bad guy, that means NOTHING")
>>> a.runAndWait()
>>> a.say("Once Bob gets the number, he divide the message by Alice's Public key")
>>> a.runAndWait()
>>> 960/3
320.0
>>> a.say("Then, Bob multiply HIS Private key with the message")
>>> a.runAndWait()
>>> 320*13
4160
>>> a.say("Notice that the original number, 64, was never sent. The messages sent was 960 and 4160")
>>> a.runAndWait()
>>> a.say("Next, Alice divide the number by her private key")
>>> a.runAndWait()
>>> 4160/5
832.0
>>> 832/13
64.0
>>> a.say(Finnaly, Bob divides the number by HIS public key")
  File "<stdin>", line 1
    a.say(Finnaly, Bob divides the number by HIS public key")
                             ^
SyntaxError: invalid syntax
>>> a.say("Finally, Bob divides the number by HIS pub
>>> a.runAndWait()
>>> 832/13
64.0
>>> a.say("I can't draw. :(")
>>> a.runAndWait()
>>> a.say("And that is the basics of encryption. Any questions?")
>>> a.runAndWait()
>>> a.say("Thank you")
>>> a.runAndWait()
>>>


