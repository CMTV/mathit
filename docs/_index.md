# Предисловие

For full documentation visit [mkdocs.org](https://mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs help` - Print this help message.

Обычная блочная формdулаdd 👹

!!! упражнение
    Содержание
    
    ??? указание
        Тут указание
        
    ??? ответ
        Тут ответ
    
[](){: #theorem-test }
    
!!! теорема
    Важная заметка

[](){: #def-test }

!!! определение
    Невероятно важное определение
    {: #fuck }
    
!!! важно
    Невероятно важная информация в блоке "Важно"
    
 a 💩-load of emojis that we use in our daily lives. See the EmojiOne demo for a list of all available emojis. Happy scrolling 🎉

$$ \int\limits^a_b f(x) = 2 + 4 $$

## Тест вопроса

??? question "Упражнение"
    <div class="conditions">
    sdt
    </div>

??? question "Упражнение с ответом"
    Тут текст
    самого
    $$ \int\limits^a_b f(x) = F(a) - F(b) $$
    упражнения
    
    ??? info "Указание"
        А тут у нас подсказочки
    
    ??? success "Ответ"
        sdfsdf
        sdf

Очень длинная блочная формула

$$ \int\limits^a_b f(x) = 2 + 4 \int\limits^a_b f(x) = 2 + 4 \int\limits^a_b f(x) = 2 + 4 $$

## Картинки

Ссылаемся на [определение](#def-test) выше.

Большая картинка

```javascript
$structure->columns = [
    'user_id' => ['type' => self::UINT, 'required' => true],
    'columns' => ['type' => self::JSON_ARRAY, 'default' => []]
];
```

Пример большого уровнения номер \eqref{eq:sample}:

\begin{equation}
  \int_0^\infty \frac{x^3}{e^x-1}\,dx = \frac{\pi^4}{15}
  \label{eq:sample}
\end{equation}

Ссылаемся на [теорему](#theorem-test) выше.

!!! Заметка
    Привет это заметка!
    
??? info sss "Заметка с кодом"
    ```javascript hl_lines="1"
        var a = '5';
    ```
    И еще тексте!
    
```tex
\begin{test} $$ a_b^c = 2 + 1 $$ \end{test}
```

[![desc](img.jpg)](img.jpg)

## Project layout

```yaml
mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
```