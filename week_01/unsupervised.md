## The Cocktail Party Algorithm

Amazingly, the method can be captured in one line of code:

```
[W,s,v] = svd((repmat(sum(x.*x,1),size(x,1),1).*x)*x');
```

