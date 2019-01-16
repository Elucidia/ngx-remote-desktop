# Installation

To use `ngx-remote-desktop` in your project install it via npm:

```
npm i @elucidia/ngx-remote-desktop --save
```

We also require two peer dependencies:

```
npm i @elucidia/guacamole-common-js --save
npm i screenfull --save
```

After installing, include `NgxRemoteDesktopModule` in your application module like this:

```typescript
import { NgModule } from '@angular/core';
import { BrowserModule } from '@angular/platform-browser';
import { NgxRemoteDesktopModule } from '@elucidia/ngx-remote-desktop';
import { AppComponent } from './app.component';

@NgModule({
  declarations: [AppComponent],
  imports: [NgxRemoteDesktopModule, BrowserModule],
  bootstrap: [AppComponent]
})
export class AppModule { }
```