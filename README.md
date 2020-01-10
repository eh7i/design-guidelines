# Design Guidelines

## Typography

### Sizes  
X-Small: `xs`  
Small: `sm`  
Medium: `md`, `default`  
Large: `lg`  
X-Large: `xl`  

### Size Unit  
```
@size-unit: 0.125
```

### Base Size
Base Size: `16px`  
rem(root element)  
```
@base-size: 16px;
```

### Font Sizes  
X-Small: `font-size-xs`  
Small: `font-size-sm`    
Medium: `font-size-md`, `font-size-base`  
Large: `font-size-lg`    
X-Large: `font-size-xl`    

```
@font-size-base: @base-size
@font-size-xs: @font-size-base * (1 - @size-unit*2)
@font-size-sm: @font-size-base * (1 - @size-unit)
@font-size-md: @font-size-base
@font-size-lg: @font-size-base * (1 + @size-unit)
@font-size-xl: @font-size-base * (1 + @size-unit*2)
```

```
@font-size-base: 16px
@font-size-xs: 12px
@font-size-sm: 14px
@font-size-md: 16px
@font-size-lg: 18px
@font-size-xl: 20px
```

### Line Height
```
14
16
20
22
24
```
