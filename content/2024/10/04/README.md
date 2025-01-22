# Awesome List Updates on Oct 04, 2024

6 awesome lists updated today.

[🏠 Home](/README.md) · [🔍 Search](https://www.trackawesomelist.com/search/) · [🔥 Feed](https://www.trackawesomelist.com/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [❤️  Sponsor](https://github.com/sponsors/theowenyoung)



## [1. Awesome Polars](/content/ddotta/awesome-polars/README.md)

### Resources / Talks and videos

*   [Polars and time series | PyData 2024](https://www.youtube.com/watch?v=qz-zAHBz6Ks) ⏳ 29 min - A video that shows how to use Polars effectively for time series analysis iby [@MarcoGorelli](https://github.com/MarcoGorelli).

## [2. Awesome Python Data Science](/content/krzjoa/awesome-python-data-science/README.md)

### Data Validation / Synthetic Data

*   [DataComPy (⭐470)](https://github.com/capitalone/datacompy)- A library to compare Pandas, Polars, and Spark data frames. It provides stats and lets users adjust for match accuracy.

## [3. Awesome Git Addons](/content/stevemao/awesome-git-addons/README.md)

### [git-exfiltrate](https://github.com/Incognito/git-exfiltrator)

### Delete branches with day-offset

    $ git branchcut execute -o 7
    Switched to branch 'main'
    Deleted branch bugfix/test (was e2afad6).
    Deleted branch too-old-branch (was 1d3f82d).

### [git-spend](https://github.com/Goutte/git-spend)

### Break apart large branches into smaller ones

Assume a hypothetical project where you make changes to two software component
folders in one feature-branch, you can use this tool to make that two branches
with a preserved history for both.

    git checkout feature-branch
    ./git-exfiltrate master feature-branch-extracted "component-folder/*"

The `feature-branch-extracted` branch will be created with just the contents of
`component-folder` from the feature-branch changes.

    *   e01009e  (main)
    |
    | * ce4ca64  (feature-branch-extracted)
    | |  component-folder/1 | 20 +
    | * f3bf092
    | |  component-folder/1 | 20 +
    * | 4b2ebd6
    |/
    |
    | * d4c374e  (feature-branch)
    | |  component-folder/1 | 20 +
    | |  different-component-folder/2 | 100 -
    | * 4724dbb
    | |  component-folder/1 | 20 +
    | |  different-component-folder/2 | 100 -
    |/
    * 927799f
    * 219e9b2

Collect and sum the `/spend <duration>` directives found in commit messages.

    $ git spend sum
    3 weeks 2 days 1 hour 37 minutes

## [4. Awesome Neovim](/content/rockerBOO/awesome-neovim/README.md)

### Remote Development / Diagnostics

*   [live-share.nvim (⭐163)](https://github.com/azratul/live-share.nvim) - Provides remote collaboration capabilities from anywhere, making it ideal for pair-programming scenarios.

## [5. Awesome Emails](/content/jonathandion/awesome-emails/README.md)

### Services / Misc

*   [Resend](https://resend.com/) - Build, test, and send transactional emails at scale.
*   [Heybounce](https://www.heybounce.io) - Email verification service that checks if an email exists and detects disposable emails.

## [6. Awesome Angular](/content/PatrickJS/awesome-angular/README.md)

### Integrations / [Google Developer Experts](https://developers.google.com/experts/all/technology/web-technologies)

*   [stream-chat-angular (⭐56)](https://github.com/GetStream/stream-chat-angular) - Angular Chat SDK ➜ Stream Chat. Build a chat app with ease.

### General / [Google Developer Experts](https://developers.google.com/experts/all/technology/web-technologies)

*   [ngx-currency (⭐239)](https://github.com/nbfontana/ngx-currency) - Currency mask module for Angular.

### Layout Components / [Google Developer Experts](https://developers.google.com/experts/all/technology/web-technologies)

*   [ngx-bottom-sheet (⭐4)](https://github.com/ArslanAmeer/ngx-bottom-sheet) - A highly customizable and lightweight Angular service that provides a mobile-friendly bottom sheet component.

---

- Prev: [Oct 05, 2024](/content/2024/10/05/README.md)
- Next: [Oct 03, 2024](/content/2024/10/03/README.md)