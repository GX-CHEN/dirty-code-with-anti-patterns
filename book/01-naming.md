# Naming is hard
Naming are generally a hard thing in life: what should I call my cat? Why this food brands sound like car? 
In programming word, we have to constantly give names to `variables`, `method/function`, `class`, `package/module`, `library` etc. This makes good naming very tricky in many situations. We don't want to name variables as `a`, `b`, `c`. But we also don't want to have super long names like `defaultPlaceholderValueForBiddingAmountBeforeUserType`.

## Overview
What cause a name to be bad?
1. Not descriptive, like `a`, `b`, `c`. When other people read the name, they cannot understand what is if for
2. Wrong name, like call `apple` as `banana`, it happens when adding new stuff and change existing code, but forgot to update the original name
3. Inaccurate name, like call `apple pie` to be `apple`
4. Acronyms or abbreviation that not intuitive for developers, for example, `bp` stands for `beloved person`
5. The names which are too long, like the verbose name example I used before `defaultPlaceholderValueForBiddingAmountBeforeUserType`


General rules to make a good name:
1. Descriptive yet concise
2. Not using unnecessary abbreviation or acronyms
3. Follow team's naming convention (camel case, connect by underscore etc.)