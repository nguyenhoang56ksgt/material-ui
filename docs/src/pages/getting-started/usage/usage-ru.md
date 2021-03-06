# Использование

<p class="description">Начните работу с React и Material-UI в кратчайшие сроки.</p>

Компоненты Material-UI работают изолированно. **Они самодостаточны** и внедрят только те стили, которые им нужны для отображения. Они не зависят от каких-либо глобальных стилей, таких как [ normalize.css ](https://github.com/necolas/normalize.css/).

Вы можете использовать любой из компонентов, как показано в документации. Пожалуйста, обратитесь к [демо-странице](/components/buttons/) каждого компонента, чтобы увидеть, как они должны быть импортированы.

## Быстрый старт

Вот краткий пример для начала, **это буквально все что вам нужно**:

```jsx
import React from 'react';
import ReactDOM from 'react-dom';
import Button from '@material-ui/core/Button';

function App() {
  return (
    <Button variant="contained" color="primary">
      Hello World
    </Button>
  );
}

ReactDOM.render(<App />, document.querySelector('#app'));
```

Да, это действительно все, что вам нужно для начала, как вы можете увидеть в этой интерактивной демонстрации:

{{"demo": "pages/getting-started/usage/Usage.js", "hideHeader": true}}

## Глобальная настройка

Опыт использования Material-UI может быть улучшен с помощью ряда важных глобальных настроек, о которых вам нужно знать.

### Responsive meta tag

Material-UI разработан используя подход Mobile First, согласно которому мы сначала пишем код для мобильных устройств, затем мастштабируем компоненты по мере необходимости, используя медиа-запросы CSS. Чтобы обеспечить правильный рендеринг и масштабирование касанием для всех устройств, добавьте метатег реагирующего окна просмотра в элемент 

<head>
  .</p> 
  
  <pre><code class="html">&lt;meta
  name="viewport"
  content="minimum-scale=1, initial-scale=1, width=device-width, shrink-to-fit=no"
/&gt;
</code></pre>
  
  <h3>
    CssBaseline
  </h3>
  
  <p>
    Material-UI предоставляет опциональный компонент <a href="/components/css-baseline/">CssBaseline</a>. Он исправляет некоторые несоответствия между браузерами и устройствами, обеспечивая несколько более упорядоченный сброс стилей HTML элементов.
  </p>
  
  <h2>
    Версионная документация
  </h2>
  
  <p>
    Данная документация всегда отражает последнюю стабильную версию Material-UI. You can find older versions of the documentation on a <a href="https://material-ui.com/versions/">separate page</a>.
  </p>
  
  <h2>
    Дальнейшие шаги
  </h2>
  
  <p>
    Теперь, когда у вас есть представление о базовых настройках, можно узнать больше:
  </p>
  
  <ul spaces="0" level="0" marker="-">
    <li level="0">
      Как предоставить <a href="/components/typography/">шрифт и оформление Material Design</a>.
    </li>
    <li level="0">
      Как воспользоваться <a href="/customization/theming/">механизмом тем</a>.
    </li>
    <li level="0">
      Как <a href="/customization/components/">переопределить</a> внешний вид компонентов.
    </li>
  </ul>