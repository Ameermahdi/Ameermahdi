
graph LR
A[Main Office (HQ)]
B(Core Router) --> C{Internet}
B --> D{Distribution Switch 1}
B --> E{Distribution Switch 2}
F[Regional Office 1] --> G(WAN Link) --> B
F --> H(Access Switch 1)
F --> I(Access Switch 2)
J(Local Server 1) --> F
K(Local Server 2) --> F
