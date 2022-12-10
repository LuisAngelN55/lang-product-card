# LANG-Product-Card

Este es un paquete de despliegue en NPM


### Luis Angel Naranjo

## Ejemplo

```
   import {ProductCard, ProductImage, ProductTitle, ProductButtons} from 'lang-product-card'
```


```

<ProductCard
    product={ product } 
    initialValues= {{
    count: 0,
    maxCount: 10
    }}
>
    {
    ( { reset, count, increaseBy, maxCount, isMaxCountReached } ) => (
        <>
        <ProductImage />
        <ProductTitle />
        <ProductButtons />  
        </>
    )
    }
</ProductCard>

```