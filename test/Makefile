# This file is part of parallelGBC, a parallel groebner basis computation tool.
#
# parallelGBC is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation, either version 3 of the License, or
# (at your option) any later version.
#
# parallelGBC is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with parallelGBC.  If not, see <http://www.gnu.org/licenses/>.
include	../Makefile.rules

OBJ=test-f4.bin lex-f4.bin

all: $(OBJ)

run:
	for i in $(OBJ); do ./$$i; done;
