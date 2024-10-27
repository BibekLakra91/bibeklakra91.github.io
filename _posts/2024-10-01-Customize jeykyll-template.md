---
layout: post
title: How to customize jeykyll template
subtitle: Understanding the flow of the codebase
gh-repo: bibeklakra91/bibeklakra91
gh-badge: [star, fork, follow]
# cover-img: /assets/img/y19.png
# thumbnail-img: /assets/img/iitk-logo.png
# share-img: /assets/img/y19.png
tags: [TemplateCustomization,CustomizationGuide,ProjectSetup,Tutorial]
author: Bibek Lakra
---

This [template](https://github.com/daattali/beautiful-jekyll) is originally developed by [Dean Attali](https://github.com/daattali). Many open source contributors have contributed ans actively participated in this project. Main key feature of this website include, very beautiful and quick hostable website, rooms for customization and very new concepts of website development. I came to know about this template from [Invictus](https://mabhay3420.github.io/) which is developed by [Abhay Mishra](https://github.com/mabhay3420).

Here is a wuick quide to setup this peoject on local machine.
### Prerequisites:
#### 1. **Ruby**: 
Jekyll is built with Ruby, so ensure you have Ruby installed. Check it with:
```javascript
ruby -v
   ```
If not installed, follow the installation instructions [here](https://www.ruby-lang.org/en/documentation/installation/).
#### 2. **Bundler**: This helps manage dependencies. Install it using:
```javascript
gem install bundler
   ```

#### 3. **Jekyll**: Install Jekyll globally:
```javascript
gem install jekyll
```

---

### Running the Jekyll Website:

#### 1. **Navigate to your project directory**:
```javascript
cd /<path-to-your-jekyll-site>
```

#### 2. **Install dependencies** (if your site has a `Gemfile`):
```
bundle install
```

#### 3. **Serve the site**:
```
bundle exec jekyll serve
```

Alternatively, if you don't use Bundler:
```
jekyll serve
```

#### 4. **Access the site**:
Open your browser and go to: [http://localhost:4000](http://localhost:4000). You can also checkout the server address in the terminal

---

### Common Issues:
- **Port already in use**: Use a different port:
   ```bash
   jekyll serve --port 8080
   ```

- **Watch mode not working**: Add `--livereload` to automatically refresh the browser on changes:
   ```bash
   jekyll serve --livereload
   ```

### Notification

**Note:** Checkout this [guide](https://beautifuljekyll.com/getstarted/) for more detailed installation. 
{: .box-note}