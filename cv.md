### 👋 my name's Nikita Rudometov

- github: @forrlyashk4
- e-mail: [nikitarudometof@gmail.com](mailto:nikitarudometof@gmail.com)
- telegram: [@forrlyashka](https://www.t.me/forrlyashka)

Hi there! I'm a novice front-end developer. I've learned
the basics of this field and am continuing my studies at the
at RS School.

**My skills:** HTML, CSS (& SASS/SCSS), JavaScript
(Promises, Fetches, etc.), Git and some Python and SQL
basics.

**Code example:**
> [169. Majority Element.](https://leetcode.com/problems/majority-element/description/?envType=study-plan-v2&envId=top-interview-150)
> Given an array nums of size n, return the majority element.
> The majority element is the element that appears more
> than ⌊n / 2⌋ times. You may assume that the majority element
> always exists in the array.

```
var majorityElement = function(nums) {
    const majorityTimes = Math.ceil(nums.length / 2);
    const checked = [];
    for (let i = 0; i < nums.length; i++) {
        if (!checked.includes(nums[i])) {
            let timesCounter = 1;
            for (let j = i + 1; j < nums.length; j++) {
                if (nums[i] === nums[j]) {
                    timesCounter++;
                }
            }
            if (timesCounter >= majorityTimes) return nums[i];
            checked.push(nums[i]);
        }
    }
};
```

**My education:**
- Web Development
  Altai State University (2021-2025)
- JavaScript + React
  [udemy course](https://www.udemy.com/course/javascript_full/)

**My English level:** B1-B2