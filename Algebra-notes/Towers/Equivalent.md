---  
title: Equivalent  
date created: Saturday, August 17th 2024, 11:32:15 am  
date modified: Saturday, August 17th 2024, 12:32:36 pm  
---  
# Equivalent  
Given two [Towers](./Tower.md) $G$ and $H$ with size $r$ and $s$ respectively,  
$G$ is equivalent to $H$ if $r=s$ and there is a permutation over their indices $i\mapsto i'$ such that:  
$G_i/G_{i+1}\approx H_{i'}/H_{i'+1}$  
In simpler terms:  
Since a [Towers](./Tower.md) splits a [Group](../Groups/Group.md) into various [Subgroups](../Groups/Subgroup.md), if we can show that both towers contain the same [Subgroups](../Groups/Subgroup.md) then they are equivalent, even if the order in which these [Subgroups](../Groups/Subgroup.md) appear is different. To do this we have a permutation over the indices of each tower making a [Map](../Mapping/Map.md) from one [Towers](./Tower.md)'s [Subgroups](../Groups/Subgroup.md) to the other's.