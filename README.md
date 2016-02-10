# simpleButton
This is a simple CSS button with 3D effect

## Buttons ##

The "buttons" can be created by adding `class="button"` to any appropriate `<a>`, `<button>`, or `<input>` element.

    <p><a href="#" class="button">Próximo passo</a></p>

Add a class `has-icon` to create a icon to the left - you need to add a `<span>` element with a `icon` class plus an available class of icon.

    <p><button class="button has-icon"><span class="icon next"></span>Próximo passo</button></p>

More examples:

    <p><a href="#" class="button has-icon disabled"><span class="icon next"></span>Próximo passo</a></p>
    <p><button class="button success">Próximo passo</button></p>
    <p><button class="button has-icon action"><span class="icon next"></span>Próximo passo</button></p>
    <p><a href="#" class="button has-icon critical"><span class="icon previous"></span>Próximo passo</a></p>
