# Curator Widget implementation using ReactJS

## Setup

In this example, we created a react component called `CuratorWidget` which accepts `feedId` property. This component will render your feed base on the Feed ID you passed. To use this, first you need to get the `FEED_ID` from your account. 

## Getting your Feed ID

Sign up to [Curator.io](https://app.curator.io/auth/register) to set up a social feed.

You'll need your unique `FEED_ID` to use the widgets.

You can find the `FEED_ID` here:

![Screenshot of Curator Admin showing FEED ID](https://user-images.githubusercontent.com/17507366/117617595-580b8b00-b19f-11eb-93fb-e4b394cccb1a.png)

## Using the FEED_ID
Using the `CuratorWidget` component, you can pass the `FEED_ID` into the `feedId` property like this.
```html
  <CuratorWidget feedId="ENTER-FEED-ID-HERE"/>
```

## Starting the App
Simply run `yarn start` to get the app running.

