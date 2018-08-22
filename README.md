# `@usertech/bliss`

Helper functions to generate [css-bliss](https://github.com/gilbox/css-bliss) class names.

# Installation

    $ yarn add https://github.com/usertech/bliss#1.0.0

# Usage

## Module

    import { bm } from '@usertech/bliss';

    <button className={bm('Button')} />
    // <button className="Button" />

    <button className={bm('Button', { red: true })} />
    // <button className="Button Button--red" />


## Element

    import { be } from '@usertech/bliss';

    <i className={be('Button', 'icon')} />
    // <i className="Button Button-icon" />

    <button className={be('Button', 'icon', { red: true })} />
    // <i className="Button Button-icon--red" />
