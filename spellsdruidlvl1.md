failed to get console mode for stdout: The handle is invalid.

Certainly! Here's an example of how you could create a D&D 5.0 spellbook using Bookdown:
```
# Bookdown book for a Level 1 Druid Spellbook

\documentclass{article}
\usepackage[utf8]{inputenc}
\usepackage{booktabs}
\title{Level 1 Druid Spellbook}
\author{Your Name}
\date{}

\begin{document}

\maketitle

% Spells
\section{Spells}

\begin{itemize}
\item \textbf{Aid}: Heals a creature within 10 feet of you for 1d4 + your druid level (hit points).
\item \textbf{Plant Growth}: A plant growing in the area grows faster than normal, and its roots grow deeper. For the duration, the plant has advantage on an attack roll or ability check made to interact with a creature within 5 feet of it.
\item \textbf{Nature's Healing Touch}: Restores 1d4 + your druid level (hit points) to a single creature you touch.
\item \textbf{Bark Skin}: Grants resistance to cold damage. Until the start of your next turn, you have advantage on saving throws against poison and resistance to poison damage.
\item \textbf{Fungal Growth}: Creatures in a 10-foot radius of you must make a Constitution saving throw (DC 15) or be slowed by the effects of fungi for 1 minute. A creature can repeat the saving throw at the end of each of its turns, with advantage on the roll if it is slower than normal.
\item \textbf{Blooming}: Creatures in a 10-foot radius of you have advantage on attack and damage rolls made using magic weapons until the start of your next turn.
\end{itemize}

% References
\section{References}

\begin{itemize}
\item \url{https://www.dandwiki.com/wiki/Level_1_Druid_(5e_CRB)}: This page provides detailed information on the Level 1 Druid class, including spellcasting and ability score improvements.
\item \url{https://www.dnd-spells.com/}: This website provides a comprehensive list of D&D spells, including those found in the Player's Handbook and other sourcebooks.
\end{itemize}

% Footnotes
\section{Footnotes}

\begin{itemize}
\item [1]: \url{https://www.dandwiki.com/wiki/Level_1_Druid_(5e_CRB)}
\item [2]: \url{https://www.dnd-spells.com/}
\end{itemize}

\end{document}
```
This will create a book with the title "Level 1 Druid Spellbook" and contain the spells you mentioned, along with references to the source material. You can customize the document as needed by adding or removing spells, modifying the formatting, etc.

Note that this is just an example, and you may need to modify it to fit your specific needs. For instance, you may want to change the spell names, add additional spells, or modify the levels at which the spells are available. Additionally, you can use Bookdown to create more complex documents, such as a multi-page book with detailed explanations of each spell and how they interact with one another.

