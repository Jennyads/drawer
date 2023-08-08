
Esse padrão de organização do teste é conhecido como AAA (Arrange, Act and Assert em inglês).
```
test('um nome que descreve o que vamos testar', () => {
    // arrumamos o cenário (por exemplo, renderizar um componente, buscamos componentes)

    // agimos (realizamos clicks, definimos valores)

    // afirmamos o que queremos (onde realizamos as expectativas)
})
```
