# michalevic

Michalevic Law Office website redesign — a static site built on Prastora.
Built on Plyń (A-Rozum/plyn): system.yaml, elements.yaml. Built on Prastora: follow its jadro invariants (root font-size per regime, no clamp, lengths in rem).
Every change keeps `python .system/tools/plyn_validate.py . --formats .system/formats` passing.
