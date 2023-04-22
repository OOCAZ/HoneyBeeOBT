# HoneyBeeOBT
HoneyBee Oral Bible Translation tool

Direction for HoneyBee development:
Those familiar with StoryPublisher will notice as they go through the concept design slides below, that HoneyBee and SPadv are very similar.  There are changes to be sure, especially on T&R and AC phases, but a vast majority of it is very similar.  So, we will be starting with the SPadv code as our base.  Also, we will be using the JSON template file, keeping as many of the tag names the same as possible.

The best template drafts, so far as being filled out the fullest, are the ones for Jonah.  They will be what we start with in designing a tool to create a database of templates and ultimately individual ZIP files that contain the required JSON, images & audio files to download to the phone app.  These Jonah templates are located at:
https://drive.google.com/drive/folders/1fmryotO3xCnjCK23Db7nC4yGdi_qknF3
https://drive.google.com/drive/u/0/folders/18tELzqSzjMKCPYK7YOW_DgJysgHVzVhv

Here are links that will be helpful:<br>
Concept design slides -- beginning about slide 10 you will find content for UI/UX modifications. 
https://docs.google.com/presentation/d/1k8fdry6r5ceF_JxErI-VG-ADXs7hvyc137I2nNAU8AQ/edit#slide=id.p

Explanation of Title, Passage Overview and Subtitle slides:
https://docs.google.com/document/d/19qVqktToNzmS8evl0Y-jqf-WwdXXT_Tf/edit?usp=share_link&ouid=106666076319626053094&rtpof=true&sd=true

Website with an explainer presentation
https://sites.google.com/view/honeybeeobt/home?authuser=0

Draft templates 
https://drive.google.com/drive/u/3/folders/1xrhak4TW5Ys8-q32gQZXe89rqMNQkt9R

StoryPublisher website
https://sites.google.com/view/spadv-website/home

StoryPublisher app on store
https://play.google.com/store/apps/details?id=org.tyndalebt.storyproduceradv

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First clone the repo to your desired dev location locally:

``` git clone <url>```

Than make sure you have the latest version of Node.js installed, look here:

https://nodejs.org/en/download

After this run this command inside of the cloned directory:

``` npx run install ```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Testing

The standard I am hoping for is to not unit test using Jest and just E2E (end to end) test with Cypress. If we have good reasons to do otherwise I am more than willing to change this.

## Tutorials

To gets started with Next (a flavor of React) with TypeScript feel free to look at the code base, ask questions and watch tutorials:

### In Depth:
https://www.youtube.com/watch?v=4lUkSgvmTYM

### Medium Length:
https://www.youtube.com/watch?v=e1EIwuO-Dlo

### Cursory:
https://www.youtube.com/watch?v=__mSgDEOyv8&t=303s&pp=ygUdZWFzeSBuZXh0IHR5cGVzY3JpcHQgdHV0b3JpYWw%3D