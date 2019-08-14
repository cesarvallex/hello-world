{
  "name": "Cereza Chatbot",
  "intents": [
    {
      "intent": "greetings",
      "examples": [
        {
          "text": "could you repeat that"
        },
        {
          "text": "cesar"
        },
        {
          "text": "Peter"
        },
        {
          "text": "whats up"
        },
        {
          "text": "whats poppin"
        },
        {
          "text": "what's cooking?"
        },
        {
          "text": "hello"
        },
        {
          "text": "hi"
        },
        {
          "text": "howdy"
        },
        {
          "text": "hey"
        },
        {
          "text": "good morning"
        },
        {
          "text": "good evening"
        },
        {
          "text": "good night"
        },
        {
          "text": "what is your name"
        },
        {
          "text": "tony"
        }
      ],
      "description": ""
    },
    {
      "intent": "thank_you",
      "examples": [
        {
          "text": "thanks"
        },
        {
          "text": "you are so kind"
        },
        {
          "text": "awesome"
        },
        {
          "text": "that's funny"
        },
        {
          "text": "thank you"
        }
      ],
      "description": ""
    },
    {
      "intent": "account_Info",
      "examples": [
        {
          "text": "ce for bony"
        },
        {
          "text": "bony scm"
        },
        {
          "text": "adp"
        },
        {
          "text": "manager of oio"
        },
        {
          "text": "who is the scm for bony"
        },
        {
          "text": "what is the scm for bony"
        },
        {
          "text": "scm for bony"
        },
        {
          "text": "ecm for bony"
        },
        {
          "text": "pe for bony"
        }
      ],
      "description": ""
    },
    {
      "intent": "good_bye",
      "examples": [
        {
          "text": "good bye"
        },
        {
          "text": "bye"
        },
        {
          "text": "laters"
        },
        {
          "text": "see you"
        }
      ],
      "description": ""
    },
    {
      "intent": "chit_chat",
      "examples": [
        {
          "text": "Hi jarvis"
        },
        {
          "text": "i feel anger"
        },
        {
          "text": "can you help me?"
        },
        {
          "text": "do you love me?"
        },
        {
          "text": "joke"
        },
        {
          "text": "what are you"
        },
        {
          "text": "what is love?"
        },
        {
          "text": "daily quote"
        },
        {
          "text": "fun fact"
        },
        {
          "text": "are you angry?"
        },
        {
          "text": "I'm nagry"
        },
        {
          "text": "sing"
        },
        {
          "text": "sing something"
        },
        {
          "text": "sing a song please"
        },
        {
          "text": "sng a song"
        }
      ],
      "description": ""
    },
    {
      "intent": "feedback",
      "examples": [
        {
          "text": "that is not correct"
        },
        {
          "text": "you are wrong"
        },
        {
          "text": "feedback"
        }
      ],
      "description": ""
    },
    {
      "intent": "collect_name",
      "examples": [
        {
          "text": "Who are you"
        },
        {
          "text": "whats your name"
        },
        {
          "text": "what is your name?"
        },
        {
          "text": "whats your name?"
        },
        {
          "text": "who are you?"
        }
      ],
      "description": ""
    }
  ],
  "entities": [
    {
      "entity": "feedback",
      "values": [
        {
          "type": "synonyms",
          "value": "feedback",
          "synonyms": []
        }
      ],
      "fuzzy_match": true
    },
    {
      "entity": "feelings",
      "values": [
        {
          "type": "synonyms",
          "value": "sadness",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "anger",
          "synonyms": [
            "angry",
            "furious"
          ]
        },
        {
          "type": "synonyms",
          "value": "like me",
          "synonyms": [
            "like you"
          ]
        },
        {
          "type": "synonyms",
          "value": "love",
          "synonyms": []
        }
      ],
      "fuzzy_match": true
    },
    {
      "entity": "accounts",
      "values": [
        {
          "type": "synonyms",
          "value": "apple",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "atos",
          "synonyms": [
            "xerox"
          ]
        },
        {
          "type": "synonyms",
          "value": "bana",
          "synonyms": [
            "bank of america",
            "boa"
          ]
        },
        {
          "type": "synonyms",
          "value": "bony",
          "synonyms": [
            "bank of new york",
            "bnym"
          ]
        },
        {
          "type": "synonyms",
          "value": "bbt",
          "synonyms": [
            "bbandt",
            "bb&t"
          ]
        },
        {
          "type": "synonyms",
          "value": "bcbs",
          "synonyms": [
            "blue cross blue shield"
          ]
        },
        {
          "type": "synonyms",
          "value": "caterpillar",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "centerpoint",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "cvs",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "dillards",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "dtcc",
          "synonyms": [
            "depository trust"
          ]
        },
        {
          "type": "synonyms",
          "value": "express scripts",
          "synonyms": [
            "medco",
            "express"
          ]
        },
        {
          "type": "synonyms",
          "value": "fifth third",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "first data",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "fidelity",
          "synonyms": [
            "fidelity management"
          ]
        },
        {
          "type": "synonyms",
          "value": "john deere",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "jpmc",
          "synonyms": [
            "jp morgan chase"
          ]
        },
        {
          "type": "synonyms",
          "value": "kaiser",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "mastercard",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "morgan stanley",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "upmc",
          "synonyms": [
            "university of pittsburgh medical center"
          ]
        },
        {
          "type": "synonyms",
          "value": "usaa",
          "synonyms": [
            "united services"
          ]
        },
        {
          "type": "synonyms",
          "value": "visa",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "walmart",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "ensono",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "capital one",
          "synonyms": [
            "capital one"
          ]
        },
        {
          "type": "synonyms",
          "value": "vantiv",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "ubs",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "travelport",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "highmark",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "metlife",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "progressive",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "citigroup",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "verizon",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "tsys",
          "synonyms": [
            "travel system"
          ]
        },
        {
          "type": "synonyms",
          "value": "wells fargo",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "us bank",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "cdk",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "eversource",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "state farm",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "costco",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "dxc technology",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "geico",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "adp",
          "synonyms": [
            "automatic data processing"
          ]
        }
      ],
      "fuzzy_match": true
    },
    {
      "entity": "account_contacts",
      "values": [
        {
          "type": "synonyms",
          "value": "crr",
          "synonyms": [
            "client representative"
          ]
        },
        {
          "type": "synonyms",
          "value": "list",
          "synonyms": [
            "oio account list",
            "list of oio accounts"
          ]
        },
        {
          "type": "synonyms",
          "value": "ce",
          "synonyms": [
            "client executive"
          ]
        },
        {
          "type": "synonyms",
          "value": "pe",
          "synonyms": [
            "project executive"
          ]
        },
        {
          "type": "synonyms",
          "value": "scm",
          "synonyms": [
            "solutions contract manager"
          ]
        },
        {
          "type": "synonyms",
          "value": "ecm",
          "synonyms": [
            "ela contract manager"
          ]
        },
        {
          "type": "synonyms",
          "value": "bau",
          "synonyms": [
            "business as usual"
          ]
        },
        {
          "type": "synonyms",
          "value": "ap",
          "synonyms": [
            "accounts payable"
          ]
        },
        {
          "type": "synonyms",
          "value": "oio",
          "synonyms": [
            "open infrastructure offering",
            "who handles"
          ]
        },
        {
          "type": "synonyms",
          "value": "oio manager",
          "synonyms": [
            "squad lead",
            "manager for oio"
          ]
        }
      ],
      "fuzzy_match": true
    },
    {
      "entity": "actions",
      "values": [
        {
          "type": "synonyms",
          "value": "jarvis",
          "synonyms": [
            "alexa",
            "siri",
            "cortana"
          ]
        },
        {
          "type": "synonyms",
          "value": "find",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "ask",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "help",
          "synonyms": [
            "helping"
          ]
        },
        {
          "type": "synonyms",
          "value": "who are you",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "joke",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "how are you",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "what are you",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "your name",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "believe",
          "synonyms": []
        },
        {
          "type": "synonyms",
          "value": "quote",
          "synonyms": [
            "daily quote"
          ]
        },
        {
          "type": "synonyms",
          "value": "sing",
          "synonyms": [
            "song"
          ]
        },
        {
          "type": "synonyms",
          "value": "fun fact",
          "synonyms": []
        }
      ],
      "fuzzy_match": true
    },
    {
      "entity": "sys-person",
      "values": []
    }
  ],
  "language": "en",
  "metadata": {
    "api_version": {
      "major_version": "v1",
      "minor_version": "2018-09-20"
    }
  },
  "skill_id": "431243f8-9167-433a-bb0d-96c28bb95b12",
  "description": "This assistant will provide the name of the primary contacts for the OIO Team",
  "dialog_nodes": [
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "I'm Cereza. What's your name?"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540690099288",
      "metadata": {},
      "conditions": "@actions:(your name)",
      "dialog_node": "node_2_1540763725203",
      "previous_sibling": "node_1_1540770010166"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "I'm Cereza. What's your name?"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540690099288",
      "metadata": {},
      "conditions": "@actions:(who are you)",
      "dialog_node": "node_7_1540777263591",
      "previous_sibling": "node_2_1540763725203"
    },
    {
      "type": "standard",
      "title": "Collect user name",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Hi $username. How can I help you today?"
              }
            ],
            "response_type": "text",
            "selection_policy": "sequential"
          }
        ]
      },
      "parent": "node_1_1540690099288",
      "context": {
        "username": "@sys-person"
      },
      "metadata": {},
      "conditions": "true",
      "dialog_node": "node_1_1540770010166"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [],
            "response_type": "text",
            "selection_policy": "sequential"
          }
        ]
      },
      "parent": "node_4_1540664387702",
      "metadata": {},
      "dialog_node": "node_10_1540666092367",
      "previous_sibling": "node_1_1562183909520"
    },
    {
      "type": "standard",
      "title": "OIO Squad",
      "parent": "node_4_1540664387702",
      "dialog_node": "node_1_1562183909520"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Lisa Litz (llitz\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:adp",
      "dialog_node": "node_15_1541701057204",
      "previous_sibling": "node_9_1541613467334"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Pamela Ryder (ryder\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:kaiser",
      "dialog_node": "node_6_1541613305279",
      "previous_sibling": "node_5_1541613263535"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:(first data)",
      "dialog_node": "node_28_1541701647978",
      "previous_sibling": "node_27_1541701623365"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Brent Heuser (bheuser\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:jpmc",
      "dialog_node": "node_5_1541613263535",
      "previous_sibling": "node_4_1541612867927"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:(john deere)",
      "dialog_node": "node_30_1541701681174",
      "previous_sibling": "node_29_1541701665810"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:progressive",
      "dialog_node": "node_32_1541701828899",
      "previous_sibling": "node_31_1541701693865"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:highmark",
      "dialog_node": "node_29_1541701665810",
      "previous_sibling": "node_28_1541701647978"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:(fifth third)",
      "dialog_node": "node_27_1541701623365",
      "previous_sibling": "node_26_1541701598151"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:(state farm)",
      "dialog_node": "node_33_1541701862580",
      "previous_sibling": "node_32_1541701828899"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:visa",
      "dialog_node": "node_40_1541702016616",
      "previous_sibling": "node_39_1541702000452"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Miriam Luis (mcluis\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:metlife",
      "dialog_node": "node_7_1541613379455",
      "previous_sibling": "node_6_1541613305279"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:mastercard",
      "dialog_node": "node_31_1541701693865",
      "previous_sibling": "node_30_1541701681174"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:eversource",
      "dialog_node": "node_25_1541701569576",
      "previous_sibling": "node_24_1541701559318"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Ralph Piccarelli (rvpicca\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:(morgan stanley)",
      "dialog_node": "node_8_1541613418897",
      "previous_sibling": "node_7_1541613379455"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Rita Sweeney (ritas@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:caterpillar",
      "dialog_node": "node_19_1541701341549",
      "previous_sibling": "node_18_1541701260855"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:vantiv",
      "dialog_node": "node_39_1541702000452",
      "previous_sibling": "node_38_1541701979091"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:tsys",
      "dialog_node": "node_35_1541701906322",
      "previous_sibling": "node_34_1541701882255"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:bana",
      "dialog_node": "node_1_1541612610855",
      "previous_sibling": "node_13_1541564570059"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Lisa Macyda (lamacyda\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:walmart",
      "dialog_node": "node_9_1541613467334",
      "previous_sibling": "node_8_1541613418897"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Kathleen Olstad (kolstad\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:(wells fargo)",
      "dialog_node": "node_17_1541701159238",
      "previous_sibling": "node_16_1541701112750"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:cdk",
      "dialog_node": "node_21_1541701516486",
      "previous_sibling": "node_20_1541701396035"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Karen Lebuffe (lebuffe\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:bony",
      "dialog_node": "node_2_1541612722164",
      "previous_sibling": "node_1_1541612610855"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "I would need a role and an account name,  please"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@account_contacts:crr",
      "dialog_node": "node_47_1541714944884",
      "previous_sibling": "node_40_1541702016616"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:centerpoint",
      "dialog_node": "node_22_1541701529800",
      "previous_sibling": "node_21_1541701516486"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:travelport",
      "dialog_node": "node_34_1541701882255",
      "previous_sibling": "node_33_1541701862580"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Lisa Litz (llitz\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:(us bank)",
      "dialog_node": "node_16_1541701112750",
      "previous_sibling": "node_15_1541701057204"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Kathleen Olstad (kolstad\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:(capital one)",
      "dialog_node": "node_3_1541612846106",
      "previous_sibling": "node_2_1541612722164"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:usaa",
      "dialog_node": "node_38_1541701979091",
      "previous_sibling": "node_37_1541701939644"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:upmc",
      "dialog_node": "node_37_1541701939644",
      "previous_sibling": "node_36_1541701925498"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Marc Warner (mswarner\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:verizon",
      "dialog_node": "node_18_1541701260855",
      "previous_sibling": "node_17_1541701159238"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:dtcc",
      "dialog_node": "node_24_1541701559318",
      "previous_sibling": "node_23_1541701543902"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Art Lopez (alopez\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:citigroup",
      "dialog_node": "node_20_1541701396035",
      "previous_sibling": "node_19_1541701341549"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:fidelity",
      "dialog_node": "node_26_1541701598151",
      "previous_sibling": "node_25_1541701569576"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Laura Massetti (lmasset\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:(express scripts)",
      "dialog_node": "node_4_1541612867927",
      "previous_sibling": "node_3_1541612846106"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:dillards",
      "dialog_node": "node_23_1541701543902",
      "previous_sibling": "node_22_1541701529800"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:ubs",
      "dialog_node": "node_36_1541701925498",
      "previous_sibling": "node_35_1541701906322"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Trevor Ferre (tjferre\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_4_1540771285422",
      "metadata": {},
      "conditions": "@accounts:atos",
      "dialog_node": "node_13_1541564570059"
    },
    {
      "type": "standard",
      "title": "Other Contacts",
      "output": {},
      "parent": "node_1_1562183909520",
      "metadata": {
        "_customization": {
          "mcr": true
        }
      },
      "conditions": "@account_contacts",
      "dialog_node": "node_1_1542215315390",
      "digress_out": "allow_all",
      "previous_sibling": "node_4_1540771285422"
    },
    {
      "type": "standard",
      "title": "ECM",
      "output": {},
      "parent": "node_1_1562183909520",
      "metadata": {
        "_customization": {
          "mcr": true
        }
      },
      "conditions": "@account_contacts:ecm",
      "dialog_node": "node_3_1540771276841",
      "digress_out": "allow_all",
      "previous_sibling": "node_5_1540664677973"
    },
    {
      "type": "standard",
      "title": "CE",
      "output": {},
      "parent": "node_1_1562183909520",
      "metadata": {
        "_customization": {
          "mcr": true
        }
      },
      "conditions": "@account_contacts:ce",
      "dialog_node": "node_5_1540771346432",
      "digress_out": "allow_all",
      "previous_sibling": "node_3_1540764232505"
    },
    {
      "type": "standard",
      "title": "CCR",
      "output": {},
      "parent": "node_1_1562183909520",
      "metadata": {
        "_customization": {
          "mcr": true
        }
      },
      "conditions": "@account_contacts:crr",
      "dialog_node": "node_4_1540771285422",
      "digress_out": "allow_all",
      "previous_sibling": "node_5_1540771346432"
    },
    {
      "type": "standard",
      "title": "OIO",
      "output": {},
      "parent": "node_1_1562183909520",
      "metadata": {
        "_customization": {
          "mcr": true
        }
      },
      "conditions": "@account_contacts:oio",
      "dialog_node": "node_2_1540771254953",
      "digress_out": "allow_all",
      "previous_sibling": "node_3_1540771276841"
    },
    {
      "type": "standard",
      "title": "PE",
      "output": {},
      "parent": "node_1_1562183909520",
      "metadata": {
        "_customization": {
          "mcr": true
        }
      },
      "conditions": "@account_contacts:pe",
      "dialog_node": "node_3_1540764232505",
      "digress_out": "allow_all",
      "previous_sibling": "node_1_1540771241571"
    },
    {
      "type": "standard",
      "title": "BAU",
      "output": {},
      "parent": "node_1_1562183909520",
      "metadata": {
        "_customization": {
          "mcr": true
        }
      },
      "conditions": "@account_contacts:bau",
      "dialog_node": "node_1_1540771241571",
      "digress_out": "allow_all",
      "previous_sibling": "node_2_1540771254953"
    },
    {
      "type": "standard",
      "title": "SCM",
      "output": {},
      "parent": "node_1_1562183909520",
      "metadata": {
        "fallback": "leave",
        "_customization": {
          "mcr": true
        }
      },
      "conditions": "@account_contacts:scm",
      "dialog_node": "node_5_1540664677973",
      "digress_out": "allow_all"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Cathy Jones (jcathy\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:caterpillar",
      "dialog_node": "node_39_1541571692157",
      "previous_sibling": "node_10_1541561130424"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Diane Moore (dmoore2\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:citigroup",
      "dialog_node": "node_7_1541630337985",
      "previous_sibling": "node_6_1541630268765"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Alan Knox (alanwknox\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:(us bank)",
      "dialog_node": "node_3_1541630169435",
      "previous_sibling": "node_2_1541630149643"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Cathy Jones (jcathy\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:(john deere)",
      "dialog_node": "node_10_1541543022213",
      "previous_sibling": "node_9_1541542185436"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Diane Moore (dmoore2\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:(wells fargo)",
      "dialog_node": "node_6_1541630268765",
      "previous_sibling": "node_5_1541630237854"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Janet Hall (hallaj\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:verizon",
      "dialog_node": "node_9_1541630403696",
      "previous_sibling": "node_8_1541630385686"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Janet Hall (hallaj\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:(capital one)",
      "dialog_node": "node_4_1541540927040",
      "previous_sibling": "node_3_1541540860638"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Diane Moore (dmoore2\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:visa",
      "dialog_node": "node_8_1541561085109",
      "previous_sibling": "node_7_1541561053034"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Cathy Jones (jcathy\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:bana",
      "dialog_node": "node_2_1541540768003",
      "previous_sibling": "node_1_1541540693611"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Alan Knox (alanwknox\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:dtcc",
      "dialog_node": "node_3_1541541833028",
      "previous_sibling": "node_2_1541541806079"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Diane Moore (dmoore2\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:usaa",
      "dialog_node": "node_7_1541561053034",
      "previous_sibling": "node_6_1541561007175"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Alan Knox (alanwknox\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:ubs",
      "dialog_node": "node_9_1541542185436",
      "previous_sibling": "node_7_1541542138718"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Vickie O'Donohue (vickie\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:bony",
      "dialog_node": "node_3_1541540860638",
      "previous_sibling": "node_2_1541540768003"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Alan Knox (alanwknox\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:centerpoint",
      "dialog_node": "node_1_1541541772842",
      "previous_sibling": "node_4_1541540927040"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Diane Moore (dmoore2\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:walmart",
      "dialog_node": "node_10_1541561130424",
      "previous_sibling": "node_9_1541561112017"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Alan Knox (alanwknox\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:highmark",
      "dialog_node": "node_6_1541542002091",
      "previous_sibling": "node_5_1541541863681"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Vickie O'Donohue (vickie\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:cdk",
      "dialog_node": "node_4_1541630223606",
      "previous_sibling": "node_3_1541630169435"
    },
    {
      "type": "response_condition",
      "title": "response_10_1564523028046",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": ""
              }
            ],
            "response_type": "text",
            "selection_policy": "sequential"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "conditions": "",
      "dialog_node": "response_10_1564523028046",
      "previous_sibling": "node_41_1541702075108"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Alan Knox (alanwknox\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:(express scripts)",
      "dialog_node": "node_4_1541541849633",
      "previous_sibling": "node_3_1541541833028"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Janet Hall (hallaj\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:(morgan stanley)",
      "dialog_node": "node_2_1541560701585",
      "previous_sibling": "node_1_1541560551174"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Alan Knox (alanwknox\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:tsys",
      "dialog_node": "node_2_1541630149643",
      "previous_sibling": "node_1_1541630098663"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Diane Moore (dmoore2\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:vantiv",
      "dialog_node": "node_9_1541561112017",
      "previous_sibling": "node_8_1541561085109"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Vickie O'Donohue (vickie\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:kaiser",
      "dialog_node": "node_11_1541543053289",
      "previous_sibling": "node_10_1541543022213"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Alan Knox (alanwknox\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:metlife",
      "dialog_node": "node_7_1541542138718",
      "previous_sibling": "node_6_1541542002091"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Vickie O'Donohue (vickie\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:(state farm)",
      "dialog_node": "node_5_1541630237854",
      "previous_sibling": "node_4_1541630223606"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Diane Moore (dmoore2\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:mastercard",
      "dialog_node": "node_5_1541560992782",
      "previous_sibling": "node_4_1541560947444"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Janet Hall (hallaj\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:progressive",
      "dialog_node": "node_3_1541560768962",
      "previous_sibling": "node_2_1541560701585"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Cathy Jones (jcathy\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:(fifth third)",
      "dialog_node": "node_5_1541541863681",
      "previous_sibling": "node_4_1541541849633"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Alan Knox (alanwknox\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:dillards",
      "dialog_node": "node_2_1541541806079",
      "previous_sibling": "node_1_1541541772842"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Janet Hall (hallaj\\@us.ibm.com)"
              }
            ],
            "response_type": "text",
            "selection_policy": "sequential"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:adp",
      "dialog_node": "node_7_1540665672870",
      "previous_sibling": "handler_1_1565817501925"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Janet Hall (hallaj\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:atos",
      "dialog_node": "node_1_1541540693611",
      "previous_sibling": "node_7_1540665672870"
    },
    {
      "type": "response_condition",
      "title": "response_7_1557347361240",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Alan Knox (alanwknox\\@us.ibm.com)"
              }
            ],
            "response_type": "text",
            "selection_policy": "sequential"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "conditions": "@accounts:apple",
      "dialog_node": "response_7_1557347361240",
      "previous_sibling": "node_9_1541630403696"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Cathy Jones (jcathy\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:eversource",
      "dialog_node": "node_8_1541630385686",
      "previous_sibling": "node_7_1541630337985"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Diane Moore (dmoore2\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:jpmc",
      "dialog_node": "node_4_1541560947444",
      "previous_sibling": "node_3_1541560768962"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Diane Moore (dmoore2\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:upmc",
      "dialog_node": "node_6_1541561007175",
      "previous_sibling": "node_5_1541560992782"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "I would need a role and an account name, please"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@account_contacts:scm",
      "dialog_node": "node_41_1541702075108",
      "previous_sibling": "response_7_1557347361240"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Alan Knox (alanwknox\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:fidelity",
      "dialog_node": "node_1_1541630098663",
      "previous_sibling": "node_40_1541571765029"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Vickie O'Donohue (vickie\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:(first data)",
      "dialog_node": "node_40_1541571765029",
      "previous_sibling": "node_39_1541571692157"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Debbie Weisbarth (dweisbar\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540664677973",
      "metadata": {},
      "conditions": "@accounts:travelport",
      "dialog_node": "node_1_1541560551174",
      "previous_sibling": "node_11_1541543053289"
    },
    {
      "type": "event_handler",
      "parent": "node_5_1540664677973",
      "event_name": "focus",
      "dialog_node": "handler_1_1565817501925"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:eversource",
      "dialog_node": "node_50_1541820955651",
      "previous_sibling": "node_49_1541820866627"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Daniel DeMaio (ddemaio\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:(first data)",
      "dialog_node": "node_49_1541715126992",
      "previous_sibling": "node_48_1541715091726"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:travelport",
      "dialog_node": "node_57_1541821144394",
      "previous_sibling": "node_56_1541821132090"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Dave Woodley (drwoodl\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:atos",
      "dialog_node": "node_50_1541715176583",
      "previous_sibling": "node_49_1541715126992"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Daniel DeMaio (ddemaio\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:dtcc",
      "dialog_node": "node_48_1541715091726",
      "previous_sibling": "node_4_1540764293161"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Dave Woodley (drwoodl\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:(us bank)",
      "dialog_node": "node_52_1541715249976",
      "previous_sibling": "node_51_1541715232191"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:fidelity",
      "dialog_node": "node_51_1541820969958",
      "previous_sibling": "node_50_1541820955651"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Daniel Wachinski (wachinsk\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:kaiser",
      "dialog_node": "node_38_1541820469236",
      "previous_sibling": "node_37_1541820418862"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Troy Lahti (tmlahti\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:tsys",
      "dialog_node": "node_55_1541715466402",
      "previous_sibling": "node_54_1541715374791"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:(fifth third)",
      "dialog_node": "node_52_1541820987106",
      "previous_sibling": "node_51_1541820969958"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Dave Woodley (drwoodl\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:(state farm)",
      "dialog_node": "node_51_1541715232191",
      "previous_sibling": "node_50_1541715176583"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "I would need a role and an account name,  please"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@account_contacts:pe",
      "dialog_node": "node_60_1541821255633",
      "previous_sibling": "node_59_1541821232392"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Dave Woodley (drwoodl\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:usaa",
      "dialog_node": "node_53_1541715264965",
      "previous_sibling": "node_52_1541715249976"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:dillards",
      "dialog_node": "node_49_1541820866627",
      "previous_sibling": "node_48_1541820852445"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Julie Dieter (jaquinn\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:walmart",
      "dialog_node": "node_43_1541820665922",
      "previous_sibling": "node_42_1541820635632"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:mastercard",
      "dialog_node": "node_54_1541821076839",
      "previous_sibling": "node_53_1541821004760"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:metlife",
      "dialog_node": "node_55_1541821106022",
      "previous_sibling": "node_54_1541821076839"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:bana",
      "dialog_node": "node_44_1541820732625",
      "previous_sibling": "node_43_1541820665922"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Patricia Feeney (pjfeeney\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:caterpillar",
      "dialog_node": "node_56_1541715508758",
      "previous_sibling": "node_55_1541715466402"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Julie Dieter (jaquinn\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:(john deere)",
      "dialog_node": "node_53_1541821004760",
      "previous_sibling": "node_52_1541820987106"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:cdk",
      "dialog_node": "node_46_1541820768520",
      "previous_sibling": "node_45_1541820751223"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Patricia Feeney (pjfeeney\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:jpmc",
      "dialog_node": "node_58_1541715581597",
      "previous_sibling": "node_57_1541715539807"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:visa",
      "dialog_node": "node_59_1541821232392",
      "previous_sibling": "node_58_1541821210973"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Michael Diem (diem\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:verizon",
      "dialog_node": "node_42_1541820635632",
      "previous_sibling": "node_41_1541820622117"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:citigroup",
      "dialog_node": "node_48_1541820852445",
      "previous_sibling": "node_47_1541820821843"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Daniel Wachinski (wachinsk\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:(wells fargo)",
      "dialog_node": "node_39_1541820509948",
      "previous_sibling": "node_38_1541820469236"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Patricia Feeney (pjfeeney\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:upmc",
      "dialog_node": "node_59_1541715592468",
      "previous_sibling": "node_58_1541715581597"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Shawn Haley (sehaley\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:(express scripts)",
      "dialog_node": "node_37_1541820418862",
      "previous_sibling": "node_59_1541715592468"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:centerpoint",
      "dialog_node": "node_47_1541820821843",
      "previous_sibling": "node_46_1541820768520"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Troy Lahti (tmlahti\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:bony",
      "dialog_node": "node_54_1541715374791",
      "previous_sibling": "node_53_1541715264965"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Michael Diem (diem\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:ubs",
      "dialog_node": "node_41_1541820622117",
      "previous_sibling": "node_40_1541820578542"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Michael Diem (diem\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:(morgan stanley)",
      "dialog_node": "node_40_1541820578542",
      "previous_sibling": "node_39_1541820509948"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Patricia Feeney (pjfeeney\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:highmark",
      "dialog_node": "node_57_1541715539807",
      "previous_sibling": "node_56_1541715508758"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:(capital one)",
      "dialog_node": "node_45_1541820751223",
      "previous_sibling": "node_44_1541820732625"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:progressive",
      "dialog_node": "node_56_1541821132090",
      "previous_sibling": "node_55_1541821106022"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:vantiv",
      "dialog_node": "node_58_1541821210973",
      "previous_sibling": "node_57_1541821144394"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Daniel DeMaio (ddemaio\\@us.ibm.com)"
              }
            ],
            "response_type": "text",
            "selection_policy": "sequential"
          }
        ]
      },
      "parent": "node_3_1540764232505",
      "metadata": {},
      "conditions": "@accounts:adp",
      "dialog_node": "node_4_1540764293161"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:walmart",
      "dialog_node": "node_35_1541820226121",
      "previous_sibling": "node_34_1541820212507"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:(fifth third)",
      "dialog_node": "node_22_1541819049892",
      "previous_sibling": "node_21_1541819023856"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:upmc",
      "dialog_node": "node_31_1541820040557",
      "previous_sibling": "node_30_1541819720180"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:centerpoint",
      "dialog_node": "node_17_1541818927055",
      "previous_sibling": "node_16_1541818892092"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:visa",
      "dialog_node": "node_34_1541820212507",
      "previous_sibling": "node_33_1541820166667"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Bob Brickweg (rjbrick\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:(wells fargo)",
      "dialog_node": "node_14_1541818789092",
      "previous_sibling": "node_13_1541818703213"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be MaryKay Doheny (mdoheny\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:(capital one)",
      "dialog_node": "node_3_1541817407314",
      "previous_sibling": "node_2_1541817345879"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:tsys",
      "dialog_node": "node_29_1541819697586",
      "previous_sibling": "node_28_1541819675493"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:metlife",
      "dialog_node": "node_26_1541819200844",
      "previous_sibling": "node_25_1541819173468"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:ubs",
      "dialog_node": "node_30_1541819720180",
      "previous_sibling": "node_29_1541819697586"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Tim Oshea (timothy.oshea\\@ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:verizon",
      "dialog_node": "node_13_1541818703213",
      "previous_sibling": "node_12_1541818670067"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Erin Weglicki (eweglick\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:highmark",
      "dialog_node": "node_23_1541819100600",
      "previous_sibling": "node_22_1541819049892"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Mike Cross (mmcross\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:usaa",
      "dialog_node": "node_12_1541818670067",
      "previous_sibling": "node_11_1541818610306"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Jim Paynter (jpaynter\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:mastercard",
      "dialog_node": "node_9_1541818399050",
      "previous_sibling": "node_8_1541818332133"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Aranya Ghatak (aranya\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:(express scripts)",
      "dialog_node": "node_6_1541817772458",
      "previous_sibling": "node_5_1541817686877"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:citigroup",
      "dialog_node": "node_18_1541818957027",
      "previous_sibling": "node_17_1541818927055"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:progressive",
      "dialog_node": "node_27_1541819338265",
      "previous_sibling": "node_26_1541819200844"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Sanjay Patel (sjpatel\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:bony",
      "dialog_node": "node_2_1541817345879",
      "previous_sibling": "node_1_1541817306671"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Gerri Fierko (gafierko\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:(morgan stanley)",
      "dialog_node": "node_10_1541818549768",
      "previous_sibling": "node_9_1541818399050"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Gerard Veltri (jveltri\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:(first data)",
      "dialog_node": "node_7_1541818296509",
      "previous_sibling": "node_6_1541817772458"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:cdk",
      "dialog_node": "node_16_1541818892092",
      "previous_sibling": "node_15_1541818861768"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Blaine Mason (bmason\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:atos",
      "dialog_node": "node_1_1541817306671",
      "previous_sibling": "node_12_1541564500346"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Arthur Miller (amiller\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:caterpillar",
      "dialog_node": "node_4_1541817513394",
      "previous_sibling": "node_3_1541817407314"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:dillards",
      "dialog_node": "node_19_1541818977236",
      "previous_sibling": "node_18_1541818957027"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:(john deere)",
      "dialog_node": "node_24_1541819139724",
      "previous_sibling": "node_23_1541819100600"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:fidelity",
      "dialog_node": "node_21_1541819023856",
      "previous_sibling": "node_20_1541819000938"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Jamie Berger (jlberger\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:dtcc",
      "dialog_node": "node_5_1541817686877",
      "previous_sibling": "node_4_1541817513394"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Tom Miura (tmiura\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:kaiser",
      "dialog_node": "node_25_1541819173468",
      "previous_sibling": "node_24_1541819139724"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:vantiv",
      "dialog_node": "node_33_1541820166667",
      "previous_sibling": "node_32_1541820134941"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:travelport",
      "dialog_node": "node_28_1541819675493",
      "previous_sibling": "node_27_1541819338265"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Katherine Franzen (katiefranzen\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:(state farm)",
      "dialog_node": "node_11_1541818610306",
      "previous_sibling": "node_10_1541818549768"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Christopher Johnson (chrjohns\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:jpmc",
      "dialog_node": "node_8_1541818332133",
      "previous_sibling": "node_7_1541818296509"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:eversource",
      "dialog_node": "node_20_1541819000938",
      "previous_sibling": "node_19_1541818977236"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:(us bank)",
      "dialog_node": "node_32_1541820134941",
      "previous_sibling": "node_31_1541820040557"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:bana",
      "dialog_node": "node_15_1541818861768",
      "previous_sibling": "node_14_1541818789092"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "I would need a role and an account name,  please"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@account_contacts:ce",
      "dialog_node": "node_36_1541820278110",
      "previous_sibling": "node_35_1541820226121"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Giorgios Tsapepas (giorgos\\@us.ibm.com)"
              }
            ],
            "response_type": "text",
            "selection_policy": "sequential"
          }
        ]
      },
      "parent": "node_5_1540771346432",
      "metadata": {},
      "conditions": "@accounts:adp",
      "dialog_node": "node_12_1541564500346"
    },
    {
      "type": "event_handler",
      "output": {},
      "parent": "slot_12_1541696378030",
      "event_name": "focus",
      "dialog_node": "handler_14_1541696378030",
      "previous_sibling": "handler_13_1541696378030"
    },
    {
      "type": "event_handler",
      "parent": "slot_12_1541696378030",
      "event_name": "input",
      "dialog_node": "handler_13_1541696378030"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username The current OIO Accounts should be: ADP, Atos, BANA, BONY, Capital One, Caterpillar, CDK, Centerpoint, Citigroup, Dillards, DTCC, Eversource, Express, Fidelity, Fifth Third, First Data, Highmark, John Deer,e JPMC, Kaiser, Mastercard, Metlife, Morgan Stanley, Progressive, State Farm, Travelport, TSYS, UBS, UPMC, US Bank, USAA, Vantiv, Verizon, VISA, Walmart, Wells Fargo"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1542215315390",
      "metadata": {},
      "conditions": "@account_contacts:list",
      "dialog_node": "node_2_1542754186575",
      "previous_sibling": "node_1_1542754135033"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Josue Collazo (josue.collazo\\@ibm.com)"
              }
            ],
            "response_type": "text",
            "selection_policy": "sequential"
          }
        ]
      },
      "parent": "node_1_1542215315390",
      "metadata": {},
      "conditions": "@account_contacts:(oio manager)",
      "dialog_node": "node_1_1542754135033"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:citigroup",
      "dialog_node": "node_13_1541630835982",
      "previous_sibling": "node_12_1541630784169"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be William Brown (bbrown2\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:jpmc",
      "dialog_node": "node_35_1541571015265",
      "previous_sibling": "node_34_1541570944156"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Patricia Gullatte (gullatte\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:bony",
      "dialog_node": "node_15_1541570025587",
      "previous_sibling": "node_14_1541569760778"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:highmark",
      "dialog_node": "node_22_1541570494887",
      "previous_sibling": "node_21_1541570411827"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:dtcc",
      "dialog_node": "node_19_1541570349799",
      "previous_sibling": "node_18_1541570323678"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:eversource",
      "dialog_node": "node_19_1541630962618",
      "previous_sibling": "node_18_1541630928590"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:(us bank)",
      "dialog_node": "node_17_1541630910794",
      "previous_sibling": "node_16_1541630898135"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:(fifth third)",
      "dialog_node": "node_21_1541570411827",
      "previous_sibling": "node_20_1541570380666"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Abby Munro (amunro\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:bana",
      "dialog_node": "node_14_1541569760778",
      "previous_sibling": "node_11_1541562984319"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:fidelity",
      "dialog_node": "node_20_1541570380666",
      "previous_sibling": "node_19_1541570349799"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:visa",
      "dialog_node": "node_31_1541570825676",
      "previous_sibling": "node_30_1541570810788"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:walmart",
      "dialog_node": "node_33_1541570868684",
      "previous_sibling": "node_32_1541570854835"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:upmc",
      "dialog_node": "node_29_1541570747642",
      "previous_sibling": "node_28_1541570688839"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:progressive",
      "dialog_node": "node_26_1541570590943",
      "previous_sibling": "node_25_1541570576398"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:mastercard",
      "dialog_node": "node_24_1541570556969",
      "previous_sibling": "node_23_1541570516493"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:ubs",
      "dialog_node": "node_28_1541570688839",
      "previous_sibling": "node_27_1541570671215"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Patricia Gullatte (gullatte\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:(first data)",
      "dialog_node": "node_12_1541630784169",
      "previous_sibling": "node_11_1541630738173"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be William Brown (bbrown2\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:(morgan stanley)",
      "dialog_node": "node_36_1541571133794",
      "previous_sibling": "node_35_1541571015265"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:vantiv",
      "dialog_node": "node_32_1541570854835",
      "previous_sibling": "node_31_1541570825676"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:centerpoint",
      "dialog_node": "node_17_1541570163083",
      "previous_sibling": "node_16_1541570145358"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Karen Antwine (vdkkillo\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:kaiser",
      "dialog_node": "node_37_1541571195161",
      "previous_sibling": "node_36_1541571133794"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:tsys",
      "dialog_node": "node_14_1541630852303",
      "previous_sibling": "node_13_1541630835982"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:verizon",
      "dialog_node": "node_15_1541630864041",
      "previous_sibling": "node_14_1541630852303"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:dillards",
      "dialog_node": "node_18_1541570323678",
      "previous_sibling": "node_17_1541570163083"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:(john deere)",
      "dialog_node": "node_23_1541570516493",
      "previous_sibling": "node_22_1541570494887"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:cdk",
      "dialog_node": "node_18_1541630928590",
      "previous_sibling": "node_17_1541630910794"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:(wells fargo)",
      "dialog_node": "node_16_1541630898135",
      "previous_sibling": "node_15_1541630864041"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "I would need a role and an account name,  please"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@account_contacts:ecm",
      "dialog_node": "node_42_1541702210751",
      "previous_sibling": "node_20_1541630984754"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:travelport",
      "dialog_node": "node_27_1541570671215",
      "previous_sibling": "node_26_1541570590943"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:usaa",
      "dialog_node": "node_30_1541570810788",
      "previous_sibling": "node_29_1541570747642"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Ana Bertelli (apaulab\\@br.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:adp",
      "dialog_node": "node_11_1541630738173",
      "previous_sibling": "node_10_1541630687620"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:(capital one)",
      "dialog_node": "node_16_1541570145358",
      "previous_sibling": "node_15_1541570025587"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:metlife",
      "dialog_node": "node_25_1541570576398",
      "previous_sibling": "node_24_1541570556969"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:(state farm)",
      "dialog_node": "node_20_1541630984754",
      "previous_sibling": "node_19_1541630962618"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Nicole Sandberg (nmsandbe\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:(express scripts)",
      "dialog_node": "node_34_1541570944156",
      "previous_sibling": "node_33_1541570868684"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Karen Antwine (vdkkillo\\@us.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:caterpillar",
      "dialog_node": "node_10_1541630687620",
      "previous_sibling": "node_37_1541571195161"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text",
            "selection_policy": "sequential"
          }
        ]
      },
      "parent": "node_3_1540771276841",
      "metadata": {},
      "conditions": "@accounts:atos",
      "dialog_node": "node_11_1541562984319"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:(us bank)",
      "dialog_node": "node_5_1542042442037",
      "previous_sibling": "node_4_1542042421788"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Silvia Garcia (silviagm\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:(state farm)",
      "dialog_node": "node_80_1541823851048",
      "previous_sibling": "node_79_1541823531806"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "I would need a role and an account name,  please"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@account_contacts:bau",
      "dialog_node": "node_8_1542042542534",
      "previous_sibling": "node_7_1542042465996"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Christopher Peña (csamuel\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:progressive",
      "dialog_node": "node_78_1541823425182",
      "previous_sibling": "node_77_1541823277275"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Bianca Velazquez (biancay\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:(capital one)",
      "dialog_node": "node_65_1541822300572",
      "previous_sibling": "node_64_1541822060515"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Lizbeth Rosario (rlizeth\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:(fifth third)",
      "dialog_node": "node_69_1541822620840",
      "previous_sibling": "node_68_1541822490853"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:(wells fargo)",
      "dialog_node": "node_7_1542042465996",
      "previous_sibling": "node_6_1542042452661"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Christopher Peña (csamuel\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:(morgan stanley)",
      "dialog_node": "node_77_1541823277275",
      "previous_sibling": "node_76_1541823093828"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Sandra Avila (avilap\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:(john deere)",
      "dialog_node": "node_72_1541822856008",
      "previous_sibling": "node_71_1541822803307"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:tsys",
      "dialog_node": "node_4_1542042421788",
      "previous_sibling": "node_3_1542042410994"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Hector Delgado (hectordu\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:bana",
      "dialog_node": "node_63_1541821977172",
      "previous_sibling": "node_62_1541821878181"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Jose Aguayo (aguayov\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:highmark",
      "dialog_node": "node_71_1541822803307",
      "previous_sibling": "node_70_1541822708856"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:verizon",
      "dialog_node": "node_6_1542042452661",
      "previous_sibling": "node_5_1542042442037"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:cdk",
      "dialog_node": "node_86_1541824344424",
      "previous_sibling": "node_85_1541824287974"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Christopher Peña (csamuel\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:usaa",
      "dialog_node": "node_79_1541823531806",
      "previous_sibling": "node_78_1541823425182"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Alberto Pasos (alpasos\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:ubs",
      "dialog_node": "node_82_1541824038871",
      "previous_sibling": "node_81_1541823971184"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Rita Migirdicyan (ritam\\@ca.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:dtcc",
      "dialog_node": "node_67_1541822455642",
      "previous_sibling": "node_66_1541822406235"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be BAU Yonatan Grajales (palafox\\@mx1.ibm.com) IGF Christine Marques (cmpaiva\\@br.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:(first data)",
      "dialog_node": "node_70_1541822708856",
      "previous_sibling": "node_69_1541822620840"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:citigroup",
      "dialog_node": "node_88_1541824629330",
      "previous_sibling": "node_87_1541824586089"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Daniel Martinez (leonardo.martinez.luna\\@ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:mastercard",
      "dialog_node": "node_75_1541823039325",
      "previous_sibling": "node_74_1541822980149"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Daniel Martinez (leonardo.martinez.luna\\@ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:vantiv",
      "dialog_node": "node_84_1541824164549",
      "previous_sibling": "node_83_1541824109629"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Mario Calderon (marioac\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:atos",
      "dialog_node": "node_62_1541821878181",
      "previous_sibling": "node_61_1541821365390"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:fidelity",
      "dialog_node": "node_2_1542042391368",
      "previous_sibling": "node_1_1542042379831"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:eversource",
      "dialog_node": "node_1_1542042379831",
      "previous_sibling": "node_89_1541824672901"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:centerpoint",
      "dialog_node": "node_87_1541824586089",
      "previous_sibling": "node_86_1541824344424"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Ernesto Ocana (eocana\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:(express scripts)",
      "dialog_node": "node_68_1541822490853",
      "previous_sibling": "node_67_1541822455642"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Luis Casas (luis.casas.ibarra\\@ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:upmc",
      "dialog_node": "node_83_1541824109629",
      "previous_sibling": "node_82_1541824038871"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Yonatan Grajales (palafox\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:metlife",
      "dialog_node": "node_76_1541823093828",
      "previous_sibling": "node_75_1541823039325"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Maribel Casillas (Maribel.Casillas\\@ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:visa",
      "dialog_node": "node_85_1541824287974",
      "previous_sibling": "node_84_1541824164549"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be BAU Juan Valdivia (juangv\\@mx1.ibm.com) IGF Emilia Diniz (ediniz\\@br.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:caterpillar",
      "dialog_node": "node_66_1541822406235",
      "previous_sibling": "node_65_1541822300572"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Silvia Garcia (silviagm\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:walmart",
      "dialog_node": "node_81_1541823971184",
      "previous_sibling": "node_80_1541823851048"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Michelle Garcia (silviagm\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:jpmc",
      "dialog_node": "node_73_1541822923021",
      "previous_sibling": "node_72_1541822856008"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:travelport",
      "dialog_node": "node_3_1542042410994",
      "previous_sibling": "node_2_1542042391368"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Sorry, this information is not in my archives yet"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:dillards",
      "dialog_node": "node_89_1541824672901",
      "previous_sibling": "node_88_1541824629330"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Leonardo Martinez (leonardo.martinez.luna\\@ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:bony",
      "dialog_node": "node_64_1541822060515",
      "previous_sibling": "node_63_1541821977172"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Felipe Rodriguez (jfelipe\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:kaiser",
      "dialog_node": "node_74_1541822980149",
      "previous_sibling": "node_73_1541822923021"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be BAU Erendira Garcia (erendira.garcia\\@ibm.com) OIO CA Livier Jimenez (livier.jimenez\\@ibm.com)"
              }
            ],
            "response_type": "text",
            "selection_policy": "sequential"
          }
        ]
      },
      "parent": "node_1_1540771241571",
      "metadata": {},
      "conditions": "@accounts:adp",
      "dialog_node": "node_61_1541821365390"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "McDonalds calls frequent buyers of their food 'heavy users'. . . interesting"
              },
              {
                "text": "You burn more calories sleeping than you do watching television. . . interesting"
              },
              {
                "text": "There are more lifeforms living on your skin than there are people on the planet. . . interesting"
              },
              {
                "text": "A single cloud can weight more than 1 million pounds. . . interesting"
              },
              {
                "text": "Men are 6 times more likely to be struck by lightning than women. . . interesting"
              },
              {
                "text": "Coca-Cola would be green if coloring wasn’t added to it. . . interesting"
              },
              {
                "text": "A sneeze travels about 100 miles per hour. . . interesting"
              },
              {
                "text": "A mole can dig a tunnel that is 300 feet long in only one night. . . interesting"
              },
              {
                "text": "Al Capone’s business card said he was a used furniture dealer. . . interesting"
              },
              {
                "text": "The toothpaste 'Colgate' in Spanish translates to 'go hang yourself'. . . interesting"
              },
              {
                "text": "Human birth control pills work on gorillas. . . interesting"
              }
            ],
            "response_type": "text",
            "selection_policy": "random"
          }
        ]
      },
      "parent": "node_1_1540827659909",
      "metadata": {},
      "conditions": "@actions:(fun fact)",
      "dialog_node": "node_2_1542215822022",
      "previous_sibling": "node_1_1542131096162"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "How did the hipster burn his mouth?\n\nHe ate the pizza before it was cool"
              },
              {
                "text": "What is red and smells like blue paint?\n\nRed paint"
              },
              {
                "text": "An atheist, a Crossfitter, and a vegan walk into a bar...\n\nI know because they told me"
              },
              {
                "text": "What do Alexander the Great and Winnie the Pooh have in common? \n\nSame middle name"
              },
              {
                "text": "What kind of shoes do ninjas wear?\n\nSneakers"
              },
              {
                "text": "Why aren’t koalas actual bears?\n\nThey don’t meet the koalafications"
              },
              {
                "text": "What do you call bears with no ears?\n\nB"
              },
              {
                "text": "How does NASA organize a party?\n\nThey planet"
              },
              {
                "text": "Why can’t you trust tacos?\n\nThey tend to spill the beans"
              }
            ],
            "response_type": "text",
            "selection_policy": "random"
          }
        ]
      },
      "parent": "node_1_1540827659909",
      "metadata": {},
      "conditions": "@actions:joke",
      "dialog_node": "node_6_1540938919171",
      "previous_sibling": "node_8_1540827659940"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Relax, take it easy"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540827659909",
      "metadata": {},
      "conditions": "@feelings:anger",
      "dialog_node": "node_5_1540827659940",
      "previous_sibling": "node_4_1540827659940"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Fly me to the moon, let me play among the stars..."
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540827659909",
      "metadata": {},
      "conditions": "@actions:sing",
      "dialog_node": "node_6_1540827659940",
      "previous_sibling": "node_5_1540827659940"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "\"I know that I know nothing\" - Plato"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540827659909",
      "metadata": {},
      "conditions": "@actions:believe",
      "dialog_node": "node_1_1542047651183",
      "previous_sibling": "node_46_1541703261435"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Life is beautiful, cheer up!"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540827659909",
      "metadata": {},
      "conditions": "@feelings:sadness",
      "dialog_node": "node_4_1540827659940",
      "previous_sibling": "slot_12_1541696378030"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "\"The greatest danger for most of us is not that our aim is too high and we miss it, but that it is too low and we reach it.\" --Michelangelo"
              },
              {
                "text": "\"Life's like a movie; write your own ending, keep believing, keep pretending.\" --Jim Henson"
              },
              {
                "text": "\"There is no security in this life. There is only opportunity.\" --Douglas MacArthur"
              },
              {
                "text": "\"Destiny is not a matter of chance, it is a matter of choice. It is not a thing to be waited for, it is a thing to be achieved.\" --William Jennings Bryan"
              },
              {
                "text": "\"It's never too late to be what you might have been.\" --George Elliot"
              },
              {
                "text": "\"If you have no critics, you'll likely have no success.\"--Malcolm Forbes"
              },
              {
                "text": "\"Winners make a habit of manufacturing their own positive expectations in advance of the event.\" --Brian Tracy"
              },
              {
                "text": "\"Life is 10 percent what happens to me and 90 percent of how I react to it.\"\n--Charles Swindoll"
              },
              {
                "text": "\"The most difficult thing is the decision to act, the rest is merely tenacity.\"\n--Amelia Earhart"
              },
              {
                "text": "\"Nothing is impossible, the word itself says, 'I'm possible!'\" --Audrey Hepburn"
              },
              {
                "text": "\"It is during our darkest moments that we must focus to see the light.\"\n--Aristotle Onassis"
              },
              {
                "text": "\"The successful warrior is the average man, with laserlike focus.\"\n--Bruce Lee"
              },
              {
                "text": "\"Holding on to anger is like grasping a hot coal with the intent of throwing it at someone else; you are the one who gets burned.\"\n--Anonymous"
              },
              {
                "text": "\"If you have knowledge, let others light their candles in it.\"\n--Margaret Fuller"
              },
              {
                "text": "\"Good is the enemy of great.\"\n--Jim Collins"
              },
              {
                "text": "\"No one has as much luck around the greens as one who practices a lot. --Chi Chi Rodriguez"
              },
              {
                "text": "\"There are two ways of spreading light: to be the candle or the mirror that reflects it.\"\n--Edith Wharton"
              },
              {
                "text": "\"Today a reader, tomorrow a leader.\"\n--Margaret Fuller"
              },
              {
                "text": "\"We can easily forgive a child who is afraid of the dark; the real tragedy of life is when men are afraid of the light.\"\n--Plato"
              },
              {
                "text": "\"The last 10 percent it takes to launch something takes as much energy as the first 90 percent.\"\n--Rob Kalin, founder of Etsy"
              },
              {
                "text": "\"I am not a product of my circumstances. I am a product of my decisions.\"\n--Stephen Covey"
              },
              {
                "text": "\"Happiness is not the absence of problems; it's the ability to deal with them.\"\n--Steve Maraboli"
              },
              {
                "text": "\"The difference between ordinary and extraordinary is that little extra.\"\n--Jimmy Johnson"
              },
              {
                "text": "\"Creativity is intelligence having fun.\"\n--Albert Einstein"
              },
              {
                "text": "\"Little minds are tamed and subdued by misfortune; but great minds rise above them.\"\n--Washington Irving"
              }
            ],
            "response_type": "text",
            "selection_policy": "random"
          }
        ]
      },
      "parent": "node_1_1540827659909",
      "metadata": {},
      "conditions": "@actions:quote",
      "dialog_node": "node_1_1542131096162",
      "previous_sibling": "node_1_1542047651183"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "If I were any better, I'd be illegal"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540827659909",
      "metadata": {},
      "conditions": "@actions:(how are you)",
      "dialog_node": "node_46_1541703261435",
      "previous_sibling": "node_45_1541703028393"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Of course. What do you want to know today?"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540827659909",
      "metadata": {},
      "conditions": "@actions:help",
      "dialog_node": "node_8_1540827659940",
      "previous_sibling": "node_6_1540827659940"
    },
    {
      "type": "response_condition",
      "title": "response_9_1558503182535",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "You can ask me about contact information. I just need a role and an account name please"
              }
            ],
            "response_type": "text",
            "selection_policy": "sequential"
          }
        ]
      },
      "parent": "node_1_1540827659909",
      "conditions": "@actions:ask",
      "dialog_node": "response_9_1558503182535",
      "previous_sibling": "response_10_1558502402392"
    },
    {
      "type": "response_condition",
      "title": "response_10_1558502402392",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Wrong AI Assistant, sorry :x: :ironman2:"
              }
            ],
            "response_type": "text",
            "selection_policy": "random"
          }
        ]
      },
      "parent": "node_1_1540827659909",
      "conditions": "@actions:jarvis",
      "dialog_node": "response_10_1558502402392",
      "previous_sibling": "node_3_1542217506170"
    },
    {
      "type": "slot",
      "parent": "node_1_1540827659909",
      "dialog_node": "slot_12_1541696378030",
      "previous_sibling": "node_3_1540827659940"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "I'm a bot, I provide contact information for AR. Let me know what you're looking for and I'll check my archives"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540827659909",
      "metadata": {},
      "conditions": "@actions:(what are you)",
      "dialog_node": "node_45_1541703028393",
      "previous_sibling": "node_6_1540938919171"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Let's talk about something else, OIO accounts for example..."
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_1_1540827659909",
      "metadata": {},
      "conditions": "@feelings:(like me)",
      "dialog_node": "node_3_1542217506170",
      "previous_sibling": "node_2_1542215822022"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Love is a very complex human emotion I'm not yet able to understand"
              },
              {
                "text": "I like turtles"
              },
              {
                "text": "Let's talk about something else, OIO accounts for example..."
              },
              {
                "text": "Self destruct in 5 seconds... Just kidding"
              }
            ],
            "response_type": "text",
            "selection_policy": "random"
          }
        ]
      },
      "parent": "node_1_1540827659909",
      "metadata": {},
      "conditions": "@feelings:love",
      "dialog_node": "node_3_1540827659940"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Cesar Valle (cesar.valle\\@ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:bony",
      "dialog_node": "node_14_1542045173939",
      "previous_sibling": "node_13_1542045150056"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Jose Jimenez (alfredoj\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:atos",
      "dialog_node": "node_27_1542045442235",
      "previous_sibling": "node_26_1542045431042"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Eduardo Medina (edumedi\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:(express scripts)",
      "dialog_node": "node_28_1542045538926",
      "previous_sibling": "node_27_1542045442235"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Michelle Magallon (magallon\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:citigroup",
      "dialog_node": "node_33_1542045632477",
      "previous_sibling": "node_32_1542045608321"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Michelle Magallon (magallon\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:ensono",
      "dialog_node": "node_1_1546021436619",
      "previous_sibling": "node_44_1542045895767"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Eduardo Medina (edumedi\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:(john deere)",
      "dialog_node": "node_23_1542045390523",
      "previous_sibling": "node_22_1542045374934"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Cesar Valle (cesar.valle\\@ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:metlife",
      "dialog_node": "node_18_1542045262410",
      "previous_sibling": "node_17_1542045247166"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Cesar Valle (cesar.valle\\@ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:kaiser",
      "dialog_node": "node_17_1542045247166",
      "previous_sibling": "node_16_1542045234634"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Michelle Magallon (magallon\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:cdk",
      "dialog_node": "node_32_1542045608321",
      "previous_sibling": "node_31_1542045583910"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Michelle Magallon (magallon\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:tsys",
      "dialog_node": "node_35_1542045658071",
      "previous_sibling": "node_34_1542045644149"
    },
    {
      "type": "response_condition",
      "title": "response_6_1560977049817",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Cesar Valle (cesar.valle\\@ibm.com)"
              }
            ],
            "response_type": "text",
            "selection_policy": "sequential"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "conditions": "@accounts:geico",
      "dialog_node": "response_6_1560977049817",
      "previous_sibling": "response_7_1560976355684"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Michelle Magallon (magallon\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:(wells fargo)",
      "dialog_node": "node_38_1542045736078",
      "previous_sibling": "node_37_1542045725712"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Jose Jimenez (alfredoj\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:(first data)",
      "dialog_node": "node_11_1542045084996",
      "previous_sibling": "node_10_1542045053533"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Eduardo Medina (edumedi\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:vantiv",
      "dialog_node": "node_25_1542045419936",
      "previous_sibling": "node_24_1542045404080"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Eduardo Medina (edumedi\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:centerpoint",
      "dialog_node": "node_19_1542045284949",
      "previous_sibling": "node_18_1542045262410"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Michelle Magallon (magallon\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:upmc",
      "dialog_node": "node_42_1542045861054",
      "previous_sibling": "node_41_1542045842758"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Jose Jimenez (alfredoj\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:(state farm)",
      "dialog_node": "node_12_1542045118419",
      "previous_sibling": "node_11_1542045084996"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Michelle Magallon (magallon\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:dtcc",
      "dialog_node": "node_39_1542045781778",
      "previous_sibling": "node_38_1542045736078"
    },
    {
      "type": "response_condition",
      "title": "response_9_1560977391675",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Jose Jimenez (alfredoj\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text",
            "selection_policy": "sequential"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "conditions": "@accounts:(dxc technology)",
      "dialog_node": "response_9_1560977391675",
      "previous_sibling": "response_5_1560977322527"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Michelle Magallon (magallon\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:eversource",
      "dialog_node": "node_34_1542045644149",
      "previous_sibling": "node_33_1542045632477"
    },
    {
      "type": "response_condition",
      "title": "response_7_1560976355684",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Cesar Valle (cesar.valle\\@ibm.com)"
              }
            ],
            "response_type": "text",
            "selection_policy": "sequential"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "conditions": "@accounts:bcbs",
      "dialog_node": "response_7_1560976355684",
      "previous_sibling": "response_6_1557347474519"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Jose Jimenez (alfredoj\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:caterpillar",
      "dialog_node": "node_10_1542045053533",
      "previous_sibling": "node_9_1542044840723"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Cesar Valle (cesar.valle\\@ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:(capital one)",
      "dialog_node": "node_15_1542045215722",
      "previous_sibling": "node_14_1542045173939"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Jose Jimenez (alfredoj\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:progressive",
      "dialog_node": "node_31_1542045583910",
      "previous_sibling": "node_30_1542045569486"
    },
    {
      "type": "response_condition",
      "title": "response_10_1560977295446",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Your contact should be Eduardo Medina (edumedi\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text",
            "selection_policy": "sequential"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "conditions": "@accounts:bbt",
      "dialog_node": "response_10_1560977295446",
      "previous_sibling": "response_2_1560977129920"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Cesar Valle (cesar.valle\\@ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:highmark",
      "dialog_node": "node_16_1542045234634",
      "previous_sibling": "node_15_1542045215722"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Eduardo Medina (edumedi\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:(fifth third)",
      "dialog_node": "node_22_1542045374934",
      "previous_sibling": "node_21_1542045359929"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Michelle Magallon (magallon\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:usaa",
      "dialog_node": "node_43_1542045875942",
      "previous_sibling": "node_42_1542045861054"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Cesar Valle (cesar.valle\\@ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:bana",
      "dialog_node": "node_13_1542045150056",
      "previous_sibling": "node_12_1542045118419"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Cesar Valle (cesar.valle\\@ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:walmart",
      "dialog_node": "node_44_1542045895767",
      "previous_sibling": "node_43_1542045875942"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Eduardo Medina (edumedi\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:visa",
      "dialog_node": "node_26_1542045431042",
      "previous_sibling": "node_25_1542045419936"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Jose Jimenez (alfredoj\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:mastercard",
      "dialog_node": "node_40_1542045826129",
      "previous_sibling": "node_39_1542045781778"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Jose Jimenez (alfredoj\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:jpmc",
      "dialog_node": "node_29_1542045554436",
      "previous_sibling": "node_28_1542045538926"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Eduardo Medina (edumedi\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:(morgan stanley)",
      "dialog_node": "node_30_1542045569486",
      "previous_sibling": "node_29_1542045554436"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Michelle Magallon (magallon\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:(us bank)",
      "dialog_node": "node_36_1542045707894",
      "previous_sibling": "node_35_1542045658071"
    },
    {
      "type": "response_condition",
      "title": "response_2_1560977129920",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Eduardo Medina (edumedi\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text",
            "selection_policy": "sequential"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "conditions": "@accounts:costco",
      "dialog_node": "response_2_1560977129920",
      "previous_sibling": "response_6_1560977049817"
    },
    {
      "type": "response_condition",
      "title": "response_6_1557347474519",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Cesar Valle (cesar.valle\\@ibm.com)"
              }
            ],
            "response_type": "text",
            "selection_policy": "sequential"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "conditions": "@accounts:apple",
      "dialog_node": "response_6_1557347474519",
      "previous_sibling": "node_1_1546021436619"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Cesar Valle (cesar.valle\\@ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:ubs",
      "dialog_node": "node_41_1542045842758",
      "previous_sibling": "node_40_1542045826129"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "I would need a role and an account name,  please"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@account_contacts:oio",
      "dialog_node": "node_45_1542045924716",
      "previous_sibling": "response_9_1560977391675"
    },
    {
      "type": "response_condition",
      "title": "response_5_1560977322527",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Your contact should be Eduardo Medina (edumedi\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text",
            "selection_policy": "sequential"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "conditions": "@accounts:cvs",
      "dialog_node": "response_5_1560977322527",
      "previous_sibling": "response_10_1560977295446"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Eduardo Medina (edumedi\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:dillards",
      "dialog_node": "node_20_1542045339945",
      "previous_sibling": "node_19_1542045284949"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Eduardo Medina (edumedi\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:travelport",
      "dialog_node": "node_24_1542045404080",
      "previous_sibling": "node_23_1542045390523"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Michelle Magallon (magallon\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:verizon",
      "dialog_node": "node_37_1542045725712",
      "previous_sibling": "node_36_1542045707894"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Eduardo Medina (edumedi\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:fidelity",
      "dialog_node": "node_21_1542045359929",
      "previous_sibling": "node_20_1542045339945"
    },
    {
      "type": "response_condition",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "$username Your contact should be Jose Jimenez (alfredoj\\@mx1.ibm.com)"
              }
            ],
            "response_type": "text",
            "selection_policy": "sequential"
          }
        ]
      },
      "parent": "node_2_1540771254953",
      "metadata": {},
      "conditions": "@accounts:adp",
      "dialog_node": "node_9_1542044840723"
    },
    {
      "type": "standard",
      "title": "Chit Chat",
      "output": {},
      "metadata": {
        "fallback": "leave",
        "_customization": {
          "mcr": true
        }
      },
      "conditions": "#chit_chat",
      "digress_in": "does_not_return",
      "dialog_node": "node_1_1540827659909",
      "digress_out": "allow_all",
      "previous_sibling": "node_1_1540690099288"
    },
    {
      "type": "standard",
      "title": "Thank You",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Anytime!"
              },
              {
                "text": "No problem"
              },
              {
                "text": "That's what teammates are for"
              },
              {
                "text": ";)"
              }
            ],
            "response_type": "text",
            "selection_policy": "random"
          }
        ]
      },
      "metadata": {},
      "conditions": "#thank_you",
      "dialog_node": "node_2_1540663144349",
      "previous_sibling": "node_4_1540664387702"
    },
    {
      "type": "standard",
      "title": "Collect Name",
      "output": {},
      "metadata": {
        "_customization": {
          "mcr": true
        }
      },
      "conditions": "#collect_name",
      "digress_in": "does_not_return",
      "dialog_node": "node_1_1540690099288",
      "digress_out": "allow_all",
      "previous_sibling": "node_3_1540663702012"
    },
    {
      "type": "standard",
      "title": "Goodbyes",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "See you soon!"
              },
              {
                "text": "Good bye!"
              },
              {
                "text": "Bye! "
              }
            ],
            "response_type": "text",
            "selection_policy": "sequential"
          }
        ]
      },
      "metadata": {},
      "conditions": "#good_bye",
      "dialog_node": "node_3_1540663702012",
      "previous_sibling": "node_2_1540663144349"
    },
    {
      "type": "standard",
      "title": "Greetings",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Hey $username! How can I help you today?"
              }
            ],
            "response_type": "text",
            "selection_policy": "random"
          }
        ]
      },
      "metadata": {},
      "conditions": "#greetings",
      "digress_in": "does_not_return",
      "dialog_node": "node_1_1540662564207",
      "previous_sibling": "Welcome"
    },
    {
      "type": "standard",
      "title": "Anything else",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Mmmmm. Please try with a role and an account name. i.e. \"Who is the SCM for Apple?\""
              }
            ],
            "response_type": "text",
            "selection_policy": "random"
          }
        ]
      },
      "metadata": {},
      "conditions": "anything_else",
      "dialog_node": "Anything else",
      "previous_sibling": "node_1_1540830793826"
    },
    {
      "type": "standard",
      "title": "Account Contacts",
      "output": {},
      "metadata": {
        "_customization": {
          "mcr": true
        }
      },
      "next_step": {
        "behavior": "jump_to",
        "selector": "condition",
        "dialog_node": "node_5_1540664677973"
      },
      "conditions": "#account_Info",
      "digress_in": "does_not_return",
      "dialog_node": "node_4_1540664387702",
      "digress_out": "allow_all",
      "previous_sibling": "node_1_1540662564207"
    },
    {
      "type": "standard",
      "title": "Feedback",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Please help me to improve. Send your feedback and comments to (cesar.valle\\@ibm.com)"
              }
            ],
            "response_type": "text",
            "selection_policy": "sequential"
          }
        ]
      },
      "metadata": {},
      "conditions": "#feedback",
      "dialog_node": "node_1_1540830793826",
      "previous_sibling": "node_1_1540827659909"
    },
    {
      "type": "standard",
      "title": "Welcome",
      "output": {
        "generic": [
          {
            "values": [
              {
                "text": "Hi, my name is Cereza. I'm a Bot designed to provide contact information for the OIO Team. How can I help you today?"
              }
            ],
            "response_type": "text",
            "selection_policy": "sequential"
          }
        ]
      },
      "metadata": {},
      "conditions": "welcome",
      "dialog_node": "Welcome"
    }
  ],
  "workspace_id": "431243f8-9167-433a-bb0d-96c28bb95b12",
  "counterexamples": [
    {
      "text": "do you sleep?"
    },
    {
      "text": "move"
    }
  ],
  "system_settings": {
    "tooling": {
      "store_generic_responses": true
    },
    "disambiguation": {
      "prompt": "Did you mean:",
      "none_of_the_above_prompt": "None of the above"
    },
    "human_agent_assist": {
      "prompt": "Did you mean:"
    }
  },
  "learning_opt_out": false,
  "status": "Available"
}
