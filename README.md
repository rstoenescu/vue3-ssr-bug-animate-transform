# Steps

1. yarn
2. yarn dev
3. Check browser console:

```
[Vue warn]: Hydration node mismatch:
- Client vnode: animateTransform
- Server rendered DOM: <animatetransform>​</animatetransform>​
  at <Home onVnodeUnmounted=fn<onVnodeUnmounted> ref=Ref< undefined > >
  at <RouterView>
  at <App>
```

# Point of interest

`/src/pages/Home.vue`. The rest of the files don't matter.
