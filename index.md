## Creating EKS & Deploying 4care components

You can use the [editor on GitHub](https://github.com/jhasgdahjg/test-pages-2/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

### Prerequisites
First: It is assumed you are testing this example from a trusted workstation with **terraform, kubectl, helm** and **AWS CLI** tools available.

Second: configure an [AWS profile](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-profiles.html) for your account aws_profile : (AWS profile is a collection of settings and credentials that you can apply to an AWS CLI command).
 
Hint: with the AWS CLI, use 

```markdown
aws configure list-profiles
```

to list the profiles you have configured and to confirm the AWS region you will be deploying in EKS.

```markdown
aws configure get region --profile <name> 
```
  



### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/jhasgdahjg/test-pages-2/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
