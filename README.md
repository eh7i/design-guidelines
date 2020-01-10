# design-guidelines

## Typography
Sizes  
X-Small: xs  
Small: sm  
Medium: md, default  
Large: lg  
X-Large: xl  

Size Unit  
@size-unit: 0.125  

Base Font Size (1rem)  
rem: root html element  
16px  
```
@font-size-base: 16px;
```

Font Sizes  
X-Small: xs  
@font-size-xs: @font-size-base * (1 - @size-unit*2) // 0.75  

Small: sm  
@font-size-sm: @font-size-base * (1 - @size-unit) // 0.875  

Medium: md, default  
@font-size-md: @font-size-base  

Large: lg  
@font-size-lg: @font-size-base * (1 + @size-unit) // 1.125  

X-Large: xl  
@font-size-xl: @font-size-base * (1 + @size-unit*2) // 1.25  
