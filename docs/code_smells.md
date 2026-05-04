# Code Smells Identified

1. Long Method — processOrder() hace demasiadas cosas.
2. Large Class — OrderService mezcla lógica, impresión, validación y almacenamiento.
3. Duplicate Code — Mensajes repetidos de errores.
4. Dead Code — unusedMethod() nunca se usa.
5. Temporary Field — tempDiscount solo se usa en un caso.
6. Feature Envy — Lógica de cálculo debería estar en otra clase.
7. Switch Statement — orderType debería ser polimorfismo.
8. Debug Flag — debugMode rompe el principio de responsabilidad única.
9. Magic Strings — "NORMAL", "PRIORITY", etc.
10. Magic Numbers — 100, 0.9, etc.