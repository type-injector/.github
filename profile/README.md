# Type Injector Lib
```@type-injector/lib``` is a small library to inject values by type or token.

* Source of the library itself: [type-injector/type-injector-lib](https://github.com/type-injector/type-injector-lib/tree/main)
* Demo integration into different frameworks: [type-injector/type-injector-lib-demo](https://github.com/type-injector/type-injector-lib-demo/tree/main)

## Features looking for contributors/sponsors
* ```@type-injector/lib```
  * special inject token to inject the TypeInjector itself
  * provide decorators
  * life-cycle to destroy a scope and its instances programmatically (without waiting for gc)
  * extend InjectConfig, so it can include a preferred scope
  
* ```@type-injector/decorated``` (doesn't exist yet)
  * optional! decorators that create the static injectConfig

* ```@type-injector/cli``` (doesn't exist yet)
  * generate a visualized (svg/md/ascii-art) dependency tree to document a project
  * static code analysis to check depdendencies without running a project
  * generate wrapper/integration code for different frameworks
  
* ```@type-injector/demo```
  * examples for additional framework integrations (e.g. stencil/viewjs)
  * improved demo documentation
  * measure+improve coverage

<!--
**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
