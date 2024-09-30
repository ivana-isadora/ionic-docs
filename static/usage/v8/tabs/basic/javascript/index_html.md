```html
<ion-tabs>
  <ion-tab tab="home">
    <div id="home-page">
      <ion-header>
        <ion-toolbar>
          <ion-title>Listen now</ion-title>
        </ion-toolbar>
      </ion-header>
      <ion-content>
        <div class="example-content">Listen now content</div>
      </ion-content>
    </div>
  </ion-tab>
  <ion-tab tab="radio">
    <div id="radio-page">
      <ion-header>
        <ion-toolbar>
          <ion-title>Radio</ion-title>
        </ion-toolbar>
      </ion-header>
      <ion-content>
        <div class="example-content">Radio content</div>
      </ion-content>
    </div>
  </ion-tab>
  <ion-tab tab="library">
    <div id="library-page">
      <ion-header>
        <ion-toolbar>
          <ion-title>Library</ion-title>
        </ion-toolbar>
      </ion-header>
      <ion-content>
        <div class="example-content">Library content</div>
      </ion-content>
    </div>
  </ion-tab>
  <ion-tab tab="search">
    <div id="search-page">
      <ion-header>
        <ion-toolbar>
          <ion-title>Search</ion-title>
        </ion-toolbar>
      </ion-header>
      <ion-content>
        <div class="example-content">Search content</div>
      </ion-content>
    </div>
  </ion-tab>

  <ion-tab-bar slot="bottom">
    <ion-tab-button tab="home">
      <ion-icon name="play-circle"></ion-icon>
      Listen Now
    </ion-tab-button>
    <ion-tab-button tab="radio">
      <ion-icon name="radio"></ion-icon>
      Radio
    </ion-tab-button>
    <ion-tab-button tab="library">
      <ion-icon name="library"></ion-icon>
      Library
    </ion-tab-button>
    <ion-tab-button tab="search">
      <ion-icon name="search"></ion-icon>
      Search
    </ion-tab-button>
  </ion-tab-bar>
</ion-tabs>

<style>
  /* This style is for demonstration purposes only. */
  /* It's not required for the tabs to function. */
  .example-content {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100%;
  }
</style>
```