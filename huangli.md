# 程序员老黄历

该工具已用 react 重写。通识原理，宜忌本身就是伪随机 + 特殊日子加权。"可能"这也是农历宜忌的基本通则。



## Random seed

A **random seed** (or **seed state**, or just **seed**) is a [number](https://en.wikipedia.org/wiki/Number "Number") (or [vector](https://en.wikipedia.org/wiki/Array_data_structure "Array data structure")) used to [initialize](https://en.wikipedia.org/wiki/Initial_condition) a [pseudorandom number generator](https://en.wikipedia.org/wiki/Pseudorandom_number_generator "Pseudorandom number generator").

For a seed to be used in a pseudorandom number generator, it does not need to be random. Because of the nature of number generating algorithms, so long as the original seed is ignored, the rest of the values that the algorithm generates will follow [probability distribution](https://en.wikipedia.org/wiki/Probability_distribution "Probability distribution") in a pseudorandom manner.

A pseudorandom number generator's number sequence is completely determined by the seed: thus, if a pseudorandom number generator is reinitialized with the same seed, it will produce the same sequence of numbers.

The choice of a good random seed is crucial in the field of [computer security](https://en.wikipedia.org/wiki/Computer_security "Computer security"). When a secret [encryption](https://en.wikipedia.org/wiki/Encryption "Encryption") [key](https://en.wikipedia.org/wiki/Key_(cryptography) "Key (cryptography)") is [pseudorandomly](https://en.wikipedia.org/wiki/Pseudorandom "Pseudorandom") [generated](https://en.wikipedia.org/wiki/Key_generation "Key generation"), having the seed will allow one to obtain the key. High [entropy](https://en.wikipedia.org/wiki/Entropy_(computing) "Entropy (computing)") is important for selecting good random seed data.<sup id="cite_ref-1" class="reference">[[1]](https://en.wikipedia.org/wiki/Random_seed#cite_note-1)</sup>

If the same _random_ seed is deliberately shared, it becomes a [secret key](https://en.wikipedia.org/wiki/Secret_key "Secret key"), so two or more systems using matching pseudorandom number algorithms and matching seeds can generate matching sequences of non-repeating numbers which can be used to synchronize remote systems, such as [GPS](https://en.wikipedia.org/wiki/GPS "GPS") satellites and receivers.

Random seeds are often generated from the state of the computer system (such as the [time](https://en.wikipedia.org/wiki/Time "Time")), a [cryptographically secure pseudorandom number generator](https://en.wikipedia.org/wiki/Cryptographically_secure_pseudorandom_number_generator "Cryptographically secure pseudorandom number generator") or from a [hardware random number generator](https://en.wikipedia.org/wiki/Hardware_random_number_generator "Hardware random number generator").

<div className="text-right"> 
    [From wiki](https://en.wikipedia.org/wiki/Random_seed)
</div>

## Pseudorandom number generator


A **pseudorandom number generator** (**PRNG**), also known as a **deterministic random bit generator** (**DRBG**),<sup id="cite_ref-1" class="reference">[[1]](https://en.wikipedia.org/wiki/Pseudorandom_number_generator#cite_note-1)</sup> is an [algorithm](https://en.wikipedia.org/wiki/Algorithm "Algorithm") for generating a sequence of numbers whose properties approximate the properties of sequences of [random numbers](https://en.wikipedia.org/wiki/Random_number_generation "Random number generation"). The PRNG-generated sequence is not truly [random](https://en.wikipedia.org/wiki/Random "Random"), because it is completely determined by an initial value, called the PRNG's _[seed](https://en.wikipedia.org/wiki/Random_seed "Random seed")_ (which may include truly random values). Although sequences that are closer to truly random can be generated using [hardware random number generators](https://en.wikipedia.org/wiki/Hardware_random_number_generator "Hardware random number generator"), _[pseudorandom](https://en.wikipedia.org/wiki/Pseudorandomness "Pseudorandomness")_ number generators are important in practice for their speed in number generation and their reproducibility.<sup id="cite_ref-2" class="reference">[[2]](https://en.wikipedia.org/wiki/Pseudorandom_number_generator#cite_note-2)</sup>

PRNGs are central in applications such as [simulations](https://en.wikipedia.org/wiki/Simulation "Simulation") (e.g. for the [Monte Carlo method](https://en.wikipedia.org/wiki/Monte_Carlo_method "Monte Carlo method")), [electronic games](https://en.wikipedia.org/wiki/Electronic_game "Electronic game") (e.g. for [procedural generation](https://en.wikipedia.org/wiki/Procedural_generation "Procedural generation")), and [cryptography](https://en.wikipedia.org/wiki/Cryptography "Cryptography"). Cryptographic applications require the output not to be predictable from earlier outputs, and more [elaborate algorithms](https://en.wikipedia.org/wiki/Cryptographically_secure_pseudorandom_number_generator "Cryptographically secure pseudorandom number generator"), which do not inherit the linearity of simpler PRNGs, are needed.

Good statistical properties are a central requirement for the output of a PRNG. In general, careful mathematical analysis is required to have any confidence that a PRNG generates numbers that are sufficiently close to random to suit the intended use. [John von Neumann](https://en.wikipedia.org/wiki/John_von_Neumann "John von Neumann") cautioned about the misinterpretation of a PRNG as a truly random generator, and joked that "Anyone who considers arithmetical methods of producing random digits is, of course, in a state of sin."<sup id="cite_ref-3" class="reference">[[3]](https://en.wikipedia.org/wiki/Pseudorandom_number_generator#cite_note-3)</sup>


<div className="text-right"> 
    [From wiki](https://en.wikipedia.org/wiki/Pseudorandom_number_generator)
</div>





## 相关参考


- [黄历上的每日宜忌是怎么算出来的？](https://www.zhihu.com/question/20167015)



