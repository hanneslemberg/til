```<input (select)="onSelect($event)">``` but ```<input [ngValue]>```, not ```<input [value]>```

``foo implements OnInit {``` but ```public ngOnInit(): void {}```

```
   [1].map(a => a + 2);
or [1].map((a:number) => a + 2);
or [1].map((a:number) => { return a + 2; });
or [1].map(function (a: number) { return a + 2 });
``` 

```[1].map(value => value * 2)``` but not ```[1].map(value => {v: value})```


 
 
```function (foo: number, bar: number|null)``` but also ```function (foo: number, bar?: number)```
