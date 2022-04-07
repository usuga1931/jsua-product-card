# JSUA-Product-Card

Este es un paquete de pruebas de NPM

### Juan Sebastian Usuga

## Ejemplo
```
import {ProductCard, ProductImage, ProductTitle, ProductButtons} from 'jsua-product-card';
```

```
<ProductCard
    product={product}
    initialValues={{
        count: 4,
        // maxCount: 10
    }}
>
    {
        ({ reset, count, isMaxCountReached, maxCount, increaseBy }) => (
            <>
                <ProductImage />
                <ProductTitle />
                <ProductButtons />
            </>
        )
    }
</ProductCard>
```