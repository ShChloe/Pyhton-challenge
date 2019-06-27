{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": 36,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['Voter ID', 'County', 'Candidate']\n",
      "3521001\n",
      "Khan: 63.00002840102243 % {2218231}\n",
      "Correy: 20.00002272084376 % {704200}\n",
      "Li: 14.000043737711193 % {492940}\n",
      "O'Tooley: 2.999999147969569 % {105630}\n"
     ]
    }
   ],
   "source": [
    "import os\n",
    "import csv\n",
    "\n",
    "path = os.path.join(\"Resources\",\"election_data.csv\")\n",
    "\n",
    "with open(path) as f:\n",
    "    reader = csv.reader(f)\n",
    "\n",
    "    columns = next(reader)\n",
    "    # first_row = next(reader)\n",
    "    print(columns)\n",
    "    \n",
    "#     for row in reader:\n",
    "#         print(row[0:3])\n",
    "\n",
    "    total_votes = 0\n",
    "    Khan = 0\n",
    "    Correy = 0\n",
    "    Li = 0\n",
    "    Tooley = 0\n",
    "    Khan_per = 0\n",
    "    Correy_per = 0\n",
    "    Li_per = 0\n",
    "    Tooley_per = 0\n",
    "\n",
    "    \n",
    "    for row in reader:\n",
    "        total_votes = total_votes + 1\n",
    "        \n",
    "        if row[2] == 'Khan': \n",
    "            Khan = Khan + 1\n",
    "            Khan_per = Khan / total_votes * 100\n",
    "#             Khan_per = total_votes / 100 * Khan\n",
    "        if row[2] == 'Correy':\n",
    "            Correy = Correy + 1\n",
    "            Correy_per = Correy / total_votes * 100\n",
    "        if row[2] == 'Li':\n",
    "            Li = Li + 1\n",
    "            Li_per = Li / total_votes * 100\n",
    "            \n",
    "        if row[2] == \"O'Tooley\":\n",
    "            Tooley = Tooley + 1\n",
    "            Tooley_per = Tooley / total_votes * 100\n",
    "            \n",
    "        \n",
    "            \n",
    "            \n",
    "        \n",
    "        \n",
    "    print(total_votes)    \n",
    "    print(\"Khan:\", Khan_per, \"%\", {(Khan)})\n",
    "    print(\"Correy:\", Correy_per, \"%\", {(Correy)})\n",
    "    print(\"Li:\", Li_per, \"%\", {(Li)})\n",
    "    print(\"O'Tooley:\", Tooley_per, \"%\", {(Tooley)})\n",
    "  "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.7.3"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
