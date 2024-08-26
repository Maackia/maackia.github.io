---
title: "Markdown Test, 마크다운 테스트"
excerpt: "추후 블로그 포스팅에 사용될 마크다운 표시 방식 테스트를 위한 글이다."

categories:
    - Blog
tags:
    - [Github.io, Markdown]

toc: true
toc_sticky: true

date: 2024-08-26
last_modified_at: 2024-08-26
---

### H1 ~ H6

```
# H1

## H2

### H3

#### H4

##### H5

###### H6
```

# H1

## H2

### H3

#### H4

##### H5

###### H6

---

`---`

### Imags

[![DSC00933.webp](/assets/images/DSC00933.webp)]

### Code

`Code`

### Code Block

```
Code block
```

### Quote

> Title
>
> > Sub Title

### Table

```
| Title                       | Date | Ratings |
| --------------------------- | ---- | ------- |
| The Super Mario Bros. Movie | 2023 | ALL     |
| Inside Out 2                | 2024 | ALL     |
```

| Title                       | Date | Ratings |
| --------------------------- | ---- | ------- |
| The Super Mario Bros. Movie | 2023 | ALL     |
| Inside Out 2                | 2024 | ALL     |

### Link

[Link](https://maackia.github.io)

`[Link](https://maackia.github.io)`

---

### List

1.  순서가 있는 목록
    1. 순서가 있는 목록
2.  순서가 있는 목록
    1. 순서가
        1. 있는
        2. 목록
            1. 입니다
3.  순서가 있는 목록

-   순서가 없는 목록
    -   순서가 없는 목록
-   순서가 없는 목록
    -   순서가
        -   없는
            -   목록
-   순서가 없는 목록

---

### Buttons

[Default Button Text](#link){: .btn}
[Primary Button Text](#link){: .btn .btn--primary}
[Success Button Text](#link){: .btn .btn--success}
[Warning Button Text](#link){: .btn .btn--warning}
[Danger Button Text](#link){: .btn .btn--danger}
[Info Button Text](#link){: .btn .btn--info}
[Inverse Button](#link){: .btn .btn--inverse}
[Light Outline Button](#link){: .btn .btn--light-outline}

[X-Large Button](#link){: .btn .btn--primary .btn--x-large}
[Large Button](#link){: .btn .btn--primary .btn--large}
[Default Button](#link){: .btn .btn--primary }
[Small Button](#link){: .btn .btn--primary .btn--small}

```
[Default Button Text](#link){: .btn}
[Primary Button Text](#link){: .btn .btn--primary}
[Success Button Text](#link){: .btn .btn--success}
[Warning Button Text](#link){: .btn .btn--warning}
[Danger Button Text](#link){: .btn .btn--danger}
[Info Button Text](#link){: .btn .btn--info}
[Inverse Button](#link){: .btn .btn--inverse}
[Light Outline Button](#link){: .btn .btn--light-outline}

[X-Large Button](#link){: .btn .btn--primary .btn--x-large}
[Large Button](#link){: .btn .btn--primary .btn--large}
[Default Button](#link){: .btn .btn--primary }
[Small Button](#link){: .btn .btn--primary .btn--small}
```

---

### Notices

**Notice:**  
기본적인 Notice
{: .notice}

**Primary Notice:**  
중요한 Notice
{: .notice--primary}

**Info Notice:**  
정보 Notice
{: .notice--info}

**Warning Notice:**  
경고 Notice
{: .notice--warning}

**Danger Notice:**  
Danger Notice
{: .notice--danger}

**Success Notice:**  
Success Notice
{: .notice--success}

```
**Notice:**
기본적인 Notice
{: .notice}

**Primary Notice:**
중요한 Notice
{: .notice--primary}

**Info Notice:**
정보 Notice
{: .notice--info}

**Warning Notice:**
경고 Notice
{: .notice--warning}

**Danger Notice:**
Danger Notice
{: .notice--danger}

**Success Notice:**
Success Notice
{: .notice--success}
```
