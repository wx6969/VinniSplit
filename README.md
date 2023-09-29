# VinniSplit

Recently, I created a hitbox for playing Street Fighter, confirming the feasibility of connecting two PCBs using a main controller board. This led to the idea of creating a split-style keyboard with specific goals in mind:

Straight Layout: Conventional staggered layouts don't feel ergonomic, and slightly curved layouts require adaptation, especially for shortcuts. Thus, I believe a split keyboard with a top-down floating layout, similar to the Corne, is the best choice.

Essential Keys: Keys like Esc, Tab, Shift, Ctrl, Win, and Alt on the left-hand side are indispensable in my workflow and must be easily accessible. This is a key reason for creating this keyboard, as many split keyboards do not retain these keys, or they change their positions, which is a pain point for me.

Left-hand Knobs: I frequently use knobs, and having them on a separate pad to the left of my keyboard requires unnecessary arm movement. To eliminate this pad, I need to incorporate two knobs directly into the keyboard.

Split Design: In practice, I rarely separate the two halves of a split keyboard (with a mouse in between). By making the keyboard compact, within 30cm, I can significantly reduce strain. A slight tilt is comfortable as it allows for more separation between the hands and a more natural wrist angle.

Top-row Numeric Keys: I believe there's room for optimization here. Ever since I started using Vial's combo functionality, inputting numbers using a combination like A and S together to get 1 has become more convenient. This reduces wrist movement for symbols as well.

The Manufacturing Process:

PCB: Creating a 4x6 grid with knobs on a 10x10 board is not easy, especially when considering the need for symmetry to accommodate components on both sides. Fortunately, it just worked out.

Because the board's length was insufficient, I had to use jumper wires.

The asymmetry of knob pins meant that jumper wires were inevitable.

Firmware: I've written three QMK firmware versions with Vial support so far. To simplify, I didn't individually map keymaps; I just included them in a large matrix. It just works!

Soldering: Jumper wires turned out to be much more interesting than I imagined. During the process, I gained a better understanding of how matrix keyboards function. Please forgive my less-than-perfect soldering.

Outer Shell CAD: I opted for acrylic again this time, as my Fusion 360 skills are a work in progress. Next time, I'll try making a curved design. By the way, is a curved keyboard really more comfortable?

In summary, I thoroughly enjoyed the process of creating this keyboard, particularly the soldering part. It feels like I've learned a lot along the way.
