# 🖥 For Developers

{% hint style="info" %}
**Good to know:** Depending on the changes you'd like to make to AutoAI's Website, we still recommend adding our website and credits to us as we spend time making tools that are open-sourced to all.
{% endhint %}

## Setting up & Deploying

Let's begin setting up AutoAI for you to edit, some key steps are introduced in this page, so we recommend reading it thoroughly.

{% tabs %}
{% tab title="Install Dependencies" %}
This simple command will help you install the required dependencies in order to make AutoAI properly function without any deployment issues.

This command is the NodeJS version to install dependencies:

```
npm i
```

You can use either NodeJS or Yarn to install the required dependencies.\
Both of the installing commands can be found here, pick either or, but in the end it will result in the same output. We recommend using NodeJS.

This command is the Yarn version to install dependencies:

```
yarn
```
{% endtab %}

{% tab title="Run Commands (NodeJS)" %}
You can use the development mode in order to run and see how your website looks before deploying it to the public. Here are the following run commands you can use.\
\
NodeJS Version:\


Development Mode:

```
npm run dev
```

Build your website:

```
npm run build
```

Startup:

```
npm run start
```
{% endtab %}

{% tab title="Run Commands (Yarn)" %}
You can use the development mode in order to run and see how your website looks before deploying it to the public. Here are the following run commands you can use.\
\
NodeJS Version:\


Development Mode:

```
yarn run dev
```

Build your website:

```
yarn run build
```
{% endtab %}

{% tab title="Deploying" %}


{% hint style="info" %}
**Quick Recommendation:** We ourselves use Vercel to fully deploy our code in seconds, it's free to connect a domain and you can make unlimited possibilities happen.
{% endhint %}

You can find our code on [GitHub](https://github.com/AutomaticAI/chat-gpt-clone). You can clone the repository and head to [Vercel's](https://vercel.com/login) website. Choose your log-in method, we recommend using "Continue with Github." \
\
Make sure you are in the "**Overview**" tab and locate the "**Add New... v**" button on the page. Select "**Project**" and open this dropdown:

![](<../.gitbook/assets/Screenshot 2023-04-19 12.01.49 PM.png>) Click the **"Add Github Account**"&#x20;

Select the place where you cloned the repository, which can be in your organization or in your private account. After installing, search for "chat-gpt-clone" and click "**Import.**" After importing the repository, you'll need to import your **ENVIRONMENTAL VARIABLES** which are the ones you used while testing.&#x20;

```javascript
OPENAI_API_KEY="YOUR_API_KEY"
```

Replace "**YOUR\_API\_KEY**" with your API Key from [OpenAI](https://platform.openai.com/). Click your profile picture (found on the top right) and click "**VIEW API KEYS**" \
\
Lastly, click Deploy and enjoy your own and updated version of AutoAI.
{% endtab %}
{% endtabs %}
