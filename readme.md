# Это заголовок для синтаксиса MD
 * [x] Изучить как устанавливается подсветка синтаксиса в редакторе Nano
 * [x] Отредактировать файл
 * [ ] Отреадактировать readme.md
 * [ ] Закомитить файл в гитхаб

HEAD -- это голова.
Коммит -- это всему голова.
Статусы файлов:
<тут пустая строка!>

```mermaid

A[untracked]--gitadd-->B[staged+tracked];
B--gitcommit-->C[tracked];
С--Изменения--> D[modified];
D--gitadd-->B;
B--Изменения-->D;
```

<и тут пустая строка!> 

```mermaid
  graph TD;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
```
