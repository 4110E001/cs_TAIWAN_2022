{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": []
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "code",
      "execution_count": 2,
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "Q_A5vXDa5C27",
        "outputId": "7c9a3826-2057-436a-aa9d-e21c06fe2a94"
      },
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Enter your name:4110E001\n",
            "Hello, 4110E001\n"
          ]
        }
      ],
      "source": [
        "x = input('Enter your name:')\n",
        "print('Hello, ' + x)"
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "a = input(\"請輸入：\")\n",
        "a"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 53
        },
        "id": "uq65yEAa6dRZ",
        "outputId": "13e83044-9607-4f1a-a457-7c6aa1609f99"
      },
      "execution_count": 3,
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "請輸入：4110E001\n"
          ]
        },
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "'4110E001'"
            ],
            "application/vnd.google.colaboratory.intrinsic+json": {
              "type": "string"
            }
          },
          "metadata": {},
          "execution_count": 3
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "a = input(\"請輸入：\")\n",
        "a\n",
        "b=a+1\n",
        "b"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 237
        },
        "id": "O1m8iAC56k24",
        "outputId": "d865d9e1-9c1a-4c95-aa1a-7c6d192f9f54"
      },
      "execution_count": 5,
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "請輸入：4110E001\n"
          ]
        },
        {
          "output_type": "error",
          "ename": "TypeError",
          "evalue": "ignored",
          "traceback": [
            "\u001b[0;31m---------------------------------------------------------------------------\u001b[0m",
            "\u001b[0;31mTypeError\u001b[0m                                 Traceback (most recent call last)",
            "\u001b[0;32m<ipython-input-5-c41d06678cb4>\u001b[0m in \u001b[0;36m<module>\u001b[0;34m\u001b[0m\n\u001b[1;32m      1\u001b[0m \u001b[0ma\u001b[0m \u001b[0;34m=\u001b[0m \u001b[0minput\u001b[0m\u001b[0;34m(\u001b[0m\u001b[0;34m\"請輸入：\"\u001b[0m\u001b[0;34m)\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[1;32m      2\u001b[0m \u001b[0ma\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0;32m----> 3\u001b[0;31m \u001b[0mb\u001b[0m\u001b[0;34m=\u001b[0m\u001b[0ma\u001b[0m\u001b[0;34m+\u001b[0m\u001b[0;36m1\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n\u001b[0m\u001b[1;32m      4\u001b[0m \u001b[0mb\u001b[0m\u001b[0;34m\u001b[0m\u001b[0;34m\u001b[0m\u001b[0m\n",
            "\u001b[0;31mTypeError\u001b[0m: can only concatenate str (not \"int\") to str"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "a = eval(input(\"請輸入：\"))\n",
        "a\n",
        "\n",
        "b=a+1\n",
        "b"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "5FSmT0tJ7cHR",
        "outputId": "52e20d4c-7e92-4669-bb46-44ddda06dc5c"
      },
      "execution_count": 6,
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "請輸入：4110E001\n"
          ]
        },
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "41101.0"
            ]
          },
          "metadata": {},
          "execution_count": 6
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "a,b = eval(input(\"請輸入兩個數位：\"))\n",
        "a,b"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "-L0Vq2Eu7iDA",
        "outputId": "47749a9a-1fac-4b52-ed93-e15af0831d4b"
      },
      "execution_count": 14,
      "outputs": [
        {
          "name": "stdout",
          "output_type": "stream",
          "text": [
            "請輸入兩個數位：10,50\n"
          ]
        },
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "(10, 50)"
            ]
          },
          "metadata": {},
          "execution_count": 14
        }
      ]
    }
  ]
}
