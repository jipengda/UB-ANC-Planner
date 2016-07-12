Copyright © 2015, 2016 Jalil Modares

This program is part of my Ph.D. Dissertation research in the Department of Electrical Engineering at the University at Buffalo. I work in UB's Multimedia Communications and Systems Laboratory with my Ph.D. adviser, Prof. Nicholas Mastronarde <http://www.eng.buffalo.edu/~nmastron/>.

If you use this program for your work/research, please cite:
J. Modares, N. Mastronarde, M. J. Medley, J. D. Matyjas, "UB-ANC: An Open Platform Testbed for Software-Defined Airborne Networking and Communications" <http://arxiv.org/abs/1509.08346>.

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see <http://www.gnu.org/licenses/>.

# UB-ANC Planner
A multi-agent coverage path planner for UB-ANC Agents

Ubuntu
------------

Run these commands to install Qt and build the planner:

```
sudo apt-get install qt5-default
git clone https://github.com/jmodares/UB-ANC-Planner
mkdir build-planner
cd build-planner
qmake ../UB-ANC-Planner
make -j4
```

IBM CPLEX Optimization Library should also be installed
