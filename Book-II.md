Book II
=======

### Chapter 1

92. "By nature" is used here as something which moves or rests of it's principle. So a plant which grows or a wolf that hunts, or an action of one of the four elements (earth, fire, air, and water) all motion because it is their _nature_ to motion. However, an object produced by an _art_ like a chair or coat do not have a _by nature_ principle of movement.

However something created from an art like a sword does have inclination to movement, ie: fall to the ground, this is not by nature of the sword but rather it's composite elements (_aka: concomitant attributes_) of iron or stone.

93. Aristotle now wants to clarify that a physician who cures himself as a patient is not cured on part of being a patient, but rather as the physician. It is accidental that the physician and patient coincide into the same person.

94-96. There is an important distinction that Aristotle wants to make. A fire goes upwards _by nature_ __not__ by the predicate of _nature_ or _has a nature_. This can be represented in psuedocode as:

```js
class Fire {
  constructor() {
    this.nature = () => [this.createHeat, this.carryFlameUpwards];

    // Perform natures
    this.createHeat()
    this.carryFlame());
  }

  createHeat() {}
  carryFlameUpwards() {}
}
```

So for `Fire` to carry a flame up, it calls the methods of `createHeat()` and `carryFlame()`. However, it's `nature()` just returns a references to what it _can do_: being `createHeat` and `carryFlame`. This means that `Fire`'s nature is only that which can be referenced by the sense or the effects of calling `createHeat()` and `carryFlameUpwards()`

Chuckle Note: Aquinas takes a little jab here at Avicenna for wanting to prove what Aristotle said you cannot: prove the existence of nature (like the blind man trying to prove to himself blueness).
