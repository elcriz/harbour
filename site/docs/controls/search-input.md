---
layout: docs
title: Search Input
---

# Search input

- [See SCSS component](../../scss/controls/search-input.scss)

## Available states

```text
search-input__input:disabled
search-input__input:focus
```

## Available modifiers

### Sizes

```text
search-input--90
search-input--max-width-60 (60, 70, 80, 90)
```

### Other

#### search-input

```text
search-input--icon
search-input--rounded-ends
search-input--button-seperated
```

#### search-input__action

```text
search-input__action--clear
search-input__action--search
```

## Structure

```text
search-input (modifier)
├── search-input__container
│   ├── search-input__input
│   ├── search-input__toolbar
│   │   ├── search-input__action (modifier)
├── search-input__button
```

## Example HTML

{% capture search-input %}
<div class="search-input">
    <div class="search-input__container">
        <input class="search-input__input">
        <div class="search-input__toolbar">
            <button class="search-input__action search-input__action--clear"></button>
        </div>
    </div>
</div>
{% endcapture %}
{% include example.html
	content=search-input
%}

{% capture search-input %}
<div class="search-input search-input--rounded-ends">
    <div class="search-input__container">
        <input class="search-input__input">
        <div class="search-input__toolbar">
            <button class="search-input__action search-input__action--clear"></button>
        </div>
    </div>
</div>
{% endcapture %}
{% include example.html
	content=search-input
%}

{% capture search-input %}
<div class="search-input search-input--rounded-ends search-input--icon">
    <div class="search-input__container">
        <input class="search-input__input">
        <div class="search-input__toolbar">
            <button class="search-input__action search-input__action--clear"></button>
        </div>
    </div>
</div>
{% endcapture %}
{% include example.html
	content=search-input
%}

### Playground

{% capture search-input %}
<div class="search-input">
    <div class="search-input__container">
        <input class="search-input__input">
        <div class="search-input__toolbar">
            <button class="search-input__action search-input__action--clear"></button>
            <button class="search-input__action search-input__action--search"></button>
        </div>
    </div>
</div>
{% endcapture %}
{% include example.html
	content=search-input
%}

{% capture search-input %}
<div class="search-input search-input--rounded-ends">
    <div class="search-input__container">
        <input class="search-input__input">
        <div class="search-input__toolbar">
            <button class="search-input__action search-input__action--clear"></button>
            <button class="search-input__action search-input__action--search"></button>
        </div>
    </div>
</div>
{% endcapture %}
{% include example.html
	content=search-input
%}

{% capture search-input %}
<div class="search-input">
    <div class="search-input__container">
        <input class="search-input__input">
        <div class="search-input__toolbar">
            <button class="search-input__action search-input__action--clear"></button>
        </div>
    </div>
    <button class="search-input__button">
        Search
    </button>
</div>
{% endcapture %}
{% include example.html
	content=search-input
%}

{% capture search-input %}
<div class="search-input search-input--rounded-ends">
    <div class="search-input__container">
        <input class="search-input__input">
        <div class="search-input__toolbar">
            <button class="search-input__action search-input__action--clear"></button>
        </div>
    </div>
    <button class="search-input__button">
        Search
    </button>
</div>
{% endcapture %}
{% include example.html
	content=search-input
%}

{% capture search-input %}
<div class="search-input search-input--button-seperated">
    <div class="search-input__container">
        <input class="search-input__input">
        <div class="search-input__toolbar">
            <button class="search-input__action search-input__action--clear"></button>
        </div>
    </div>
    <button class="search-input__button">
        Search
    </button>
</div>
{% endcapture %}
{% include example.html
	content=search-input
%}

{% capture search-input %}
<div class="search-input search-input--rounded-ends search-input--button-seperated">
    <div class="search-input__container">
        <input class="search-input__input">
        <div class="search-input__toolbar">
            <button class="search-input__action search-input__action--clear"></button>
        </div>
    </div>
    <button class="search-input__button">
        Search
    </button>
</div>
{% endcapture %}
{% include example.html
	content=search-input
%}