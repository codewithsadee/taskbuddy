# Essential Stuff

## Html import links

Google font

``` html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&display=swap" rel="stylesheet">
```

Ionicon

``` html
<script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
<script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>
```

---

## Colors

``` css
--granite-gray: hsl(210, 1%, 37%);
--eerie-black: hsl(240, 2%, 11%);
--slimy-green: hsl(91, 100%, 30%);
--fuzzy-wuzzy: hsl(0, 42%, 57%);
--davys-gray: hsl(220, 2%, 28%);
--cultured-1: hsl(228, 17%, 94%);
--cultured-2: hsl(0, 0%, 96%);
--dim-gray: hsl(240, 1%, 41%);
--white_80: hsla(0, 0%, 100%, 0.8);
--white_70: hsla(0, 0%, 100%, 0.7);
--white_40: hsla(0, 0%, 100%, 0.4);
--white_10: hsla(0, 0%, 100%, 0.1);
--black_05: hsla(0, 0%, 0%, 0.05);
--black_50: hsla(0, 0%, 0%, 0.5);
--black_25: hsla(0, 0%, 0%, 0.25);
--white-2: hsl(0, 0%, 98%);
--white-1: hsl(0, 0%, 100%);
--black: hsl(0, 0%, 0%);
```

## Theme colors

``` css
--hue: 227;
--theme-bg: linear-gradient(to bottom, 
              hsl(var(--hue, 227), 40%, 50%), 
              hsl(var(--hue, 227), 40%, 60%));
--theme-color: hsl(var(--hue, 227), 42%, 57%);
```

## Typography

``` css
--ff-roboto: "Roboto", sans-serif;

--fs-1: 2.6rem;
--fs-2: 2.2rem;
--fs-3: 1.8rem;
--fs-4: 1.4rem;
--fs-5: 1.2rem;

--fw-500: 500;
```

## Radius

``` css
--radius-4: 4px;
--radius-5: 5px;
--radius-10: 10px;
```

## Shadow

``` css
--shadow-1: 0 0 5px hsla(0, 0%, 0%, 0.05);
--shadow-2: 0 0 10px hsla(0, 0%, 0%, 0.05);
```

## Transition

``` css
--transition: 0.15s ease;
--cubic-out: cubic-bezier(0.05, 0.65, 0.25, 1);
```
