{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": 1,
   "id": "04d2ee66-48c6-46c8-b206-c2a674d57e60",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Hello, World!\n"
     ]
    }
   ],
   "source": [
    "print(\"Hello, World!\")\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 2,
   "id": "738452f4-4488-44ed-a288-005088c24b88",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "[85, 72, 90, 65, 88]\n"
     ]
    }
   ],
   "source": [
    "marks = [85, 72, 90, 65, 88]\n",
    "print(marks)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 3,
   "id": "5dc8de93-9bbc-44f6-ab15-25fe999961b5",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "85\n"
     ]
    }
   ],
   "source": [
    "print(marks[0])"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 4,
   "id": "852688d8-1d0d-4b74-80a7-0da581369100",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "90\n"
     ]
    }
   ],
   "source": [
    "print(marks[2])"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 5,
   "id": "bc72d248-2694-4564-8fec-7717e52abc03",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "[85, 72, 90, 65, 88, 95]\n"
     ]
    }
   ],
   "source": [
    "marks.append(95)\n",
    "print(marks)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 6,
   "id": "fcc422b3-c92e-4b72-9313-666b08dddd23",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "6\n"
     ]
    }
   ],
   "source": [
    "print(len(marks))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 7,
   "id": "5f29a685-48a8-43d3-96a8-738f7ee4a655",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['Yash', 'Rahul', 'Priya', 'Aman']\n",
      "[85, 72, 90, 65]\n"
     ]
    }
   ],
   "source": [
    "student_names = [\"Yash\", \"Rahul\", \"Priya\", \"Aman\"]\n",
    "\n",
    "scores = [85, 72, 90, 65]\n",
    "\n",
    "print(student_names)\n",
    "print(scores)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 8,
   "id": "a5d509b4-4860-4509-9957-9fb4e7637fa8",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "{'name': 'Yash', 'age': 21, 'course': 'BTech CSE', 'marks': 85}\n"
     ]
    }
   ],
   "source": [
    "student = {\n",
    "    \"name\": \"Yash\",\n",
    "    \"age\": 21,\n",
    "    \"course\": \"BTech CSE\",\n",
    "    \"marks\": 85\n",
    "}\n",
    "\n",
    "print(student)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 9,
   "id": "1c95fedf-bf77-4ef3-ac15-91f7e6938ad1",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Yash\n"
     ]
    }
   ],
   "source": [
    "print(student[\"name\"])"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 10,
   "id": "8044551d-b303-491a-ac57-39b5145a1223",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "85\n"
     ]
    }
   ],
   "source": [
    "print(student[\"marks\"])"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 11,
   "id": "e633f9bc-f7b2-45ab-9c9b-a30941d7adda",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "{'name': 'Yash', 'age': 21, 'course': 'BTech CSE', 'marks': 85, 'city': 'Delhi'}\n"
     ]
    }
   ],
   "source": [
    "student[\"city\"] = \"Delhi\"\n",
    "\n",
    "print(student)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 12,
   "id": "8d57bb7c-31eb-45cc-85b1-6aa93a0964ad",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "90\n"
     ]
    }
   ],
   "source": [
    "student[\"marks\"] = 90\n",
    "\n",
    "print(student[\"marks\"])"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 13,
   "id": "ce04bcb1-a76b-4205-bb35-ce3ddc1f348a",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "{'name': 'Yash', 'course': 'BTech CSE', 'marks': 90, 'city': 'Delhi'}\n"
     ]
    }
   ],
   "source": [
    "student.pop(\"age\")\n",
    "\n",
    "print(student)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 14,
   "id": "a0316c97-779e-4eb2-a1e7-6be0aefde8f4",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "85\n",
      "72\n",
      "90\n",
      "65\n",
      "88\n"
     ]
    }
   ],
   "source": [
    "marks = [85, 72, 90, 65, 88]\n",
    "\n",
    "for mark in marks:\n",
    "    print(mark)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 15,
   "id": "512c5c45-98dc-4725-929f-e8421a0e3e97",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "90\n",
      "77\n",
      "95\n",
      "70\n",
      "93\n"
     ]
    }
   ],
   "source": [
    "marks = [85, 72, 90, 65, 88]\n",
    "\n",
    "for mark in marks:\n",
    "    print(mark + 5)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 16,
   "id": "92c5a690-0022-4543-8a19-7a8793f84312",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "85 Excellent\n",
      "90 Excellent\n",
      "88 Excellent\n"
     ]
    }
   ],
   "source": [
    "marks = [85, 72, 90, 65, 88]\n",
    "\n",
    "for mark in marks:\n",
    "    if mark >= 80:\n",
    "        print(mark, \"Excellent\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 17,
   "id": "4ff7752f-4742-46da-90b2-a1dfafa4fc62",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "1\n",
      "2\n",
      "3\n",
      "4\n",
      "5\n"
     ]
    }
   ],
   "source": [
    "count = 1\n",
    "\n",
    "while count <= 5:\n",
    "    print(count)\n",
    "    count = count + 1"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 21,
   "id": "56c33521-9112-42f1-898f-155da26822c6",
   "metadata": {},
   "outputs": [],
   "source": [
    "def greet():\n",
    "    print(\"Hello, welcome to Python!\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 22,
   "id": "f3789308-9617-4dc2-9253-368cac4b8591",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Hello, welcome to Python!\n"
     ]
    }
   ],
   "source": [
    "greet()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 23,
   "id": "cf60e23b-7163-43c5-bbb4-f6a463cbfde4",
   "metadata": {},
   "outputs": [],
   "source": [
    "def greet(name):\n",
    "    print(\"Hello\", name)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 24,
   "id": "2473efc5-c14c-4aca-b641-83a7fddd0344",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Hello Yash\n"
     ]
    }
   ],
   "source": [
    "greet(\"Yash\")"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 25,
   "id": "5824d5d9-23e2-4651-8674-28a23a16b0ae",
   "metadata": {},
   "outputs": [],
   "source": [
    "def add_numbers(a, b):\n",
    "    return a + b"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 26,
   "id": "dd703ce9-3645-4f06-a1ac-0ef6d97a26ca",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "30\n"
     ]
    }
   ],
   "source": [
    "result = add_numbers(10, 20)\n",
    "print(result)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 28,
   "id": "d869532e-71fc-4886-beb9-040f611e7ab0",
   "metadata": {},
   "outputs": [],
   "source": [
    "def calculate_average(numbers):\n",
    "    total = sum(numbers)\n",
    "    average = total / len(numbers)\n",
    "    return average"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 29,
   "id": "94f605cc-5068-4188-b098-5e555a05aa0f",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "84.0\n"
     ]
    }
   ],
   "source": [
    "marks = [80, 90, 70, 85, 95]\n",
    "\n",
    "result = calculate_average(marks)\n",
    "\n",
    "print(result)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 2,
   "id": "f0afc46d-4288-4ca2-9cf4-f8009aa36e80",
   "metadata": {},
   "outputs": [],
   "source": [
    "file = open(\"marks.txt\", \"w\")\n",
    "file.write(\"80\\n90\\n70\\n85\\n95\")\n",
    "file.close()"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 3,
   "id": "02818561-a19c-46d0-95db-24f6b9815695",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "80\n",
      "90\n",
      "70\n",
      "85\n",
      "95\n"
     ]
    }
   ],
   "source": [
    "file = open(\"marks.txt\", \"r\")\n",
    "data = file.read()\n",
    "file.close()\n",
    "\n",
    "print(data)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 4,
   "id": "c737219d-cdae-4595-aae7-28209607966d",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "80\n",
      "90\n",
      "70\n",
      "85\n",
      "95\n"
     ]
    }
   ],
   "source": [
    "with open(\"marks.txt\", \"r\") as file:\n",
    "    data = file.read()\n",
    "\n",
    "print(data)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 5,
   "id": "08525078-bda2-4949-81e2-5ab2d99eeafb",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "80\n",
      "90\n",
      "70\n",
      "85\n",
      "95\n"
     ]
    }
   ],
   "source": [
    "with open(\"marks.txt\", \"r\") as file:\n",
    "    for line in file:\n",
    "        print(line.strip())"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 6,
   "id": "9c239583-24a5-413a-b9bf-9ccf837d0d18",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "[80, 90, 70, 85, 95]\n"
     ]
    }
   ],
   "source": [
    "with open(\"marks.txt\", \"r\") as file:\n",
    "    marks = [int(line.strip()) for line in file]\n",
    "\n",
    "print(marks)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 7,
   "id": "da555590-e1c3-4f8a-afd4-0f7e113ac071",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Average marks: 84.0\n"
     ]
    }
   ],
   "source": [
    "average = sum(marks) / len(marks)\n",
    "\n",
    "print(\"Average marks:\", average)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 8,
   "id": "5ef04429-c1de-47ee-8e2a-68329d3f081d",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Average marks: 84.0\n"
     ]
    }
   ],
   "source": [
    "def calculate_average_from_file(filename):\n",
    "    with open(filename, \"r\") as file:\n",
    "        marks = [int(line.strip()) for line in file]\n",
    "\n",
    "    return sum(marks) / len(marks)\n",
    "\n",
    "\n",
    "result = calculate_average_from_file(\"marks.txt\")\n",
    "\n",
    "print(\"Average marks:\", result)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 9,
   "id": "cfb3da46-2670-42a0-8bde-9ea31814cc20",
   "metadata": {},
   "outputs": [
    {
     "ename": "ModuleNotFoundError",
     "evalue": "No module named 'numpy'",
     "output_type": "error",
     "traceback": [
      "\u001b[31m---------------------------------------------------------------------------\u001b[39m",
      "\u001b[31mModuleNotFoundError\u001b[39m                       Traceback (most recent call last)",
      "\u001b[36mCell\u001b[39m\u001b[36m \u001b[39m\u001b[32mIn[9]\u001b[39m\u001b[32m, line 1\u001b[39m\n\u001b[32m----> \u001b[39m\u001b[32m1\u001b[39m \u001b[38;5;28;01mimport\u001b[39;00m numpy \u001b[38;5;28;01mas\u001b[39;00m np\n\u001b[32m      2\u001b[39m \u001b[38;5;28;01mimport\u001b[39;00m pandas \u001b[38;5;28;01mas\u001b[39;00m pd\n\u001b[32m      3\u001b[39m \n\u001b[32m      4\u001b[39m print(\u001b[33m\"NumPy version:\"\u001b[39m, np.__version__)\n",
      "\u001b[31mModuleNotFoundError\u001b[39m: No module named 'numpy'"
     ]
    }
   ],
   "source": [
    "import numpy as np\n",
    "import pandas as pd\n",
    "\n",
    "print(\"NumPy version:\", np.__version__)\n",
    "print(\"Pandas version:\", pd.__version__)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 11,
   "id": "1492cf6e-d5a1-40f6-86c1-1ed0d56a11b1",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "/home/anshu/.local/share/uv/tools/jupyterlab/bin/python: No module named pip\n",
      "Note: you may need to restart the kernel to use updated packages.\n"
     ]
    }
   ],
   "source": [
    "%pip install numpy pandas"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 12,
   "id": "680e7aef-d212-4cce-b5df-aa8bd04c64ac",
   "metadata": {},
   "outputs": [
    {
     "ename": "ModuleNotFoundError",
     "evalue": "No module named 'numpy'",
     "output_type": "error",
     "traceback": [
      "\u001b[31m---------------------------------------------------------------------------\u001b[39m",
      "\u001b[31mModuleNotFoundError\u001b[39m                       Traceback (most recent call last)",
      "\u001b[36mCell\u001b[39m\u001b[36m \u001b[39m\u001b[32mIn[12]\u001b[39m\u001b[32m, line 1\u001b[39m\n\u001b[32m----> \u001b[39m\u001b[32m1\u001b[39m \u001b[38;5;28;01mimport\u001b[39;00m numpy \u001b[38;5;28;01mas\u001b[39;00m np\n\u001b[32m      2\u001b[39m \u001b[38;5;28;01mimport\u001b[39;00m pandas \u001b[38;5;28;01mas\u001b[39;00m pd\n\u001b[32m      3\u001b[39m \n\u001b[32m      4\u001b[39m print(\u001b[33m\"NumPy version:\"\u001b[39m, np.__version__)\n",
      "\u001b[31mModuleNotFoundError\u001b[39m: No module named 'numpy'"
     ]
    }
   ],
   "source": [
    "import numpy as np\n",
    "import pandas as pd\n",
    "\n",
    "print(\"NumPy version:\", np.__version__)\n",
    "print(\"Pandas version:\", pd.__version__)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 13,
   "id": "c51d5076-0d34-4772-958b-fa5cee01127c",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "/home/anshu/.local/share/uv/tools/jupyterlab/bin/python\n"
     ]
    }
   ],
   "source": [
    "import sys\n",
    "print(sys.executable)"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 14,
   "id": "ee4a430b-5c6d-4caa-96e9-eed3ccf7b85b",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "/home/anshu/.local/share/uv/tools/jupyterlab/bin/python: No module named pip\n"
     ]
    }
   ],
   "source": [
    "import sys\n",
    "!{sys.executable} -m pip install numpy pandas"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "b0c58e11-8db7-4169-99d8-b582857aace9",
   "metadata": {},
   "outputs": [],
   "source": [
    "import sys\n",
    "!{sys.executable} -m pip install numpy pandas\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "f564e9de-1b5c-424c-a0d2-cbfc8c0ea8a2",
   "metadata": {},
   "outputs": [],
   "source": [
    "import numpy as np\n",
    "import pandas as pd\n",
    "\n",
    "print(\"NumPy version:\", np.__version__)\n",
    "print(\"Pandas version:\", pd.__version__)\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "98cf0011-f8ff-4b10-a956-736c96808007",
   "metadata": {},
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "8005becb-4928-4c51-9bed-42bdecb08085",
   "metadata": {},
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "3eda617e-8de3-4e2d-ab57-d6189c6e5faf",
   "metadata": {},
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "6bdea55f-2a8f-46b4-8a6d-69d0df763589",
   "metadata": {},
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "8cf84f72-5fd9-4c8b-b6e4-ae93a067d01f",
   "metadata": {},
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "97642cc5-2361-45e8-af0a-7133a3a9ffbe",
   "metadata": {},
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "cb1b5e32-178e-4792-8e8f-e7c96b3100fa",
   "metadata": {},
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "40963c41-41e6-4eb8-9f3f-328d7f6da792",
   "metadata": {},
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "00fd8de9-9fd8-4875-9d8c-8eff83cc22c4",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
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
   "version": "3.12.3"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
