# Vietnamese Hybrid G2P with Regional Variations
# 🎯 Project Overview

This project explores Grapheme-to-Phoneme (G2P) conversion for Vietnamese, focusing on regional accent variations (Northern, Central, and Southern).
We propose a hybrid approach combining rule-based mapping with a lightweight neural network, aiming to handle ambiguous or unseen words more effectively than traditional systems.

# 🧩 Motivation

While existing G2P systems for Vietnamese focus on standard Northern pronunciation, regional diversity introduces significant phonetic differences (e.g., “r”, “d”, “gi” are distinct across regions).
A purely rule-based system lacks adaptability, while a purely neural system struggles with limited phonetic data.
Hence, this project proposes a hybrid system that blends linguistic rules + neural correction for better accuracy and interpretability.

# 🧠 Research Questions

How do existing Vietnamese G2P systems perform across regional variations?

Can a hybrid rule-based + neural network approach improve phoneme accuracy for ambiguous words?

What are the trade-offs between rule-based transparency and neural adaptability?