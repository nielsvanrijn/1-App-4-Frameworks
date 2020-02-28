# 1 App 4 Frameworks
This repo serves as a collection page with all the different framework repo's as submodules.\
Overarching will be here as well (UML, Design, etc...)


## Approach
My initial plan is to make the app in:

- [ ] Laravel + Vue
- [ ] API + Angular
- [ ] API + React
- [ ] API + Vue

Depending on how far I get with Laravel + Vue, I will also do Vue separately.

I will use Bootstrap 4 with some customizations. As the apps get more comlex I will add more custom styles to get closer to the design.

## Design
###### To be continued...

```typescript
Vue.directive('focus', {
    inserted: function (el) {
        el.focus();
    },
    update: function (el, binding) {
        var value = binding.value;
        if (value) {
            Vue.nextTick(function () {
                el.focus();
            });
        }
    }
});
```
