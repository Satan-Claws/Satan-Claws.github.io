---
title: 11-Cycle
layout: default
permalink: /problems/11-cycle/
published: true
---

You are given an array $a$ of $n$ distinct integers.

For positions $1 \leq i < j < k \leq n$, if $(a_i \oplus a_j) \lor (a_j \oplus a_k) < 32$, you are allowed to shift $(a_i, a_j, a_k)$ to $(a_j, a_k, a_i)$.

This operation can be done as many times as required without any cost.

What is the lexicographically smallest array that can be created using this? \\
