# The-Game-of-Life
John Conway's Game of Life

세포 자동자 게임.
바둑판처럼 정사각형의 여러 칸으로 나뉘어진 공간에서 한 칸에 한 마리씩 있는 세포들의 삶과 죽음이 펼쳐지는 게임이다
처음 세포들의 위치를 입력하면 그 규칙에 따라 삶과 죽음이 일어나는 것


[RULE]
다음 세대로 넘어갈 때 세포들의 생사가 결정되는데, 인접한 8개의 칸을 기준으로 하며 그 기준은 다음과 같다.
- 죽은 칸과 인접한 8칸 중 정확히 3칸에 세포가 살아 있다면 해당 칸의 세포는 그 다음 세대에 살아난다.
- 살아있는 칸과 인접한 8칸 중 2칸 혹은 3칸에 세포가 살아 있다면 해당 칸의 세포는 살아있는 상태를 유지한다.
- 그 이외의 경우 해당 칸의 세포는 다음 세대에 고립돼 죽거나 혹은 주위가 너무 복잡해져서 죽는다. 혹은 죽은 상태를 유지한다.