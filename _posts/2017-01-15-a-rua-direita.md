---
date: 2017-01-15
title: A Rua Direita
video_id: LbQ-q9IFTvY
description: Um teste sobre a Rua Direita
categories:
  - 3d
resources:
  - name: Um link
    link: https://github.com/CloudCannon/creative-jekyll-theme/
  - name: Outro link
    link: https://cloudcannon.com
type: Video
set: getting-started
set_order: 1
---


Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit,  [veniamn](https://cloudcannon.com).

## Lorem ipsum

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum

## explicabo

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.


Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem.


 Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur

## veniam

Next, we need to do is to define areas in our HTML which non-developers can update. These are called [Editable Regions](https://docs.cloudcannon.com/editing/editable-regions/) and are set by adding a class of `editable` to HTML elements.

Open `index.html` in CloudCannon and add a class of `editable` to the `h1` and `p` inside `<div class="header-content-inner">` so it becomes the following:

~~~ html
<div class="header-content-inner">
  <h1 class="editable">Your Favorite Source of Free Bootstrap Themes</h1>
  <hr>
  <p class="editable">Start Bootstrap can help you build better websites using the Bootstrap CSS framework! Just download your template and start going, no strings attached!</p>
  <a href="/about.html" class="btn btn-primary btn-xl page-scroll">Find Out More</a>
</div>
~~~

## Client Access

Now the site is ready for our non-developer to update. We'll set up [Client Sharing](https://docs.cloudcannon.com/sharing/client-sharing/) which allows our client to update their site without having to create an account. Go to the Site Settings / Client Sharing section and set a password for your client.

Our non-developer can view their live site at your-site.cloudvent.net (or you can set up a custom domain). To update their site they just add `/update` to the URL and enter the password we set earlier.

## The Client Workflow

Once the client logs in they see their site with colored boxes highlighting the editable regions. The client can update content directly inline by clicking on text:

By clicking _Collections_ in the sidebar the client can manage their blog posts:

Editing posts happens in the [Content Editor](https://docs.cloudcannon.com/editing/content-editor/) which is a rich text editor for Markdown. The client can also manage all the front matter data on the page using an easy-to-use editor:

Or we can use the [Visual Editor](https://docs.cloudcannon.com/editing/visual-editor/) to update posts:

The client can also update collection items using the same editor. In this example there's no body content and only front matter so we've made the front matter editor full screen:

If we have GitHub, Bitbucket or Dropbox connected to the site, all changes the client makes are pushed back to the storage provider.

Now the client can update all the content and hasn't had to learn HTML, Liquid or Markdown. This gives a small taste of what you can achieve on CloudCannon. [Sign up free](https://app.cloudcannon.com/users/sign_up) and make your Jekyll site client editable.
