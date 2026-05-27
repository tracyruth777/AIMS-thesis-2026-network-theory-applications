# Report Analysis Code- Applications of Network Theory
## AIMS Ghana — MSc Mathematical Sciences, 2026

##Description
Comparative empirical analysis of structural balance across social and geopolitical signed temporal networks, using a three families of balance measures spanning combinatorial, spectral, and walk-based balance measures.

## Abstract
Structural balance defines the tendency of relationships to organise into tension-free configurations. This is depicted by the principles that 'the friend of my friend is my friend' and 'the enemy of my enemy is my friend'. Signed networks provide the framework for measuring balance by representing friendship and enmity as positive and negative edges. Many studies have investigated balance measure behaviour on static signed networks, but have not extended it to evolving networks. We compare three families of balance measures across four signed temporal networks, and systematically vary their sign proportions. Results show that not all networks tend towards balance over time, with some exhibiting oscillatory behaviour. Additionally, measure agreement is not guaranteed, indicating that measure choice strongly affects the classification of structural balance.

## Requirements
pip install networkx numpy scipy matplotlib pandas seaborn

## Usage
Run 01_cleaning_and_graphs.ipynb first, then 02_analysis_and_figures.ipynb.

## Data Sources
- Van de Bunt (1999). https://www.stats.ox.ac.uk/~snijders/siena/vdBunt_data.htm
- Aref et al. (2020). https://doi.org/10.6084/m9.figshare.12152628
- Palmer et al. (2022). Conflict Management and Peace Science, 39(4), 470-482.
- Gibler (2008). International Military Alliances, 1648-2008. CQ Press.
