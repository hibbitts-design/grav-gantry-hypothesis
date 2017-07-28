# Gantry 5 'Hypothesis' Atom for Grav

Atoms are small, modular blocks with preset scripting that enable you to add elements to your Grav Gantry 5 pages.

## Installing the Atom

Before installing and using the Atom, it is suggested you temporarily enable Gantry's [`Development Mode`](http://docs.gantry.org/gantry5/configure/extras)

1. Open the folder for your active theme in the `user/data/gantry5/themes/` folder of your Gantry installation. For example, if you are using the Helium theme open the folder `user/data/gantry5/themes/g5_helium`.
2. If a `particles` folder already exists within the theme folder open it, otherwise create it.
3. Upload `hypothesis.html.twig` and `hypothesis.yaml` files into the `particles` folder. For example, if you are using the Helium theme copy the two particle files into `user/data/gantry5/themes/g5_helium/particles`.

## Using the Atom
1. Add the Atom to your theme's 'Atoms' area on the 'Page Settings' panel.

## Page Options
Once the particle is installed, Grav pages will support the following Page Header/FrontMatter option:

```
hide_hypothesis: true    # hide Hypothesis sidebar on this page
```
