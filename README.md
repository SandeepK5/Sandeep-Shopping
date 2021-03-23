https://teams.microsoft.com/l/meetup-join/19:meeting_MWNiOTBjMDItNjE2ZS00ZjllLTk2MDMtYzA1ZDI2NjZiN2U0@thread.v2/0?context=%7B%22Tid%22:%225d135798-0ae4-4f20-a663-a223e2cd1f4e%22,%22Oid%22:%229e69573d-b789-46d0-8984-ba3d84aeaa1e%22%7D


https://teams.microsoft.com/l/meetup-join/19:meeting_NTI5Y2RkOGUtODNiNS00ZmI3LTg4NTItY2NlMTJiZjBjZmRj@thread.v2/0?context=%7B%22Tid%22:%22d3a74ac8-efe4-4fe8-b707-b1bf8c6a25bd%22,%22Oid%22:%22e7b39b78-ae65-4340-ab2c-f0cbe0792671%22%7D


{
    "cam": {
        "aliases": {},
        "mappings": {
            "properties": {
                "_timestamp": {
                    "type": "long"
                },
                "id": {
                    "type": "long"
                },
                "name": {
                    "type": "text",
                    "fields": {
                        "keyword": {
                            "type": "keyword",
                            "ignore_above": 256
                        }
                    }
                },
                "scores": {
                    "properties": {
                        "Automated Security Test Cases": {
                            "properties": {
                                "name": {
                                    "type": "text",
                                    "fields": {
                                        "keyword": {
                                            "type": "keyword",
                                            "ignore_above": 256
                                        }
                                    }
                                },
                                "value": {
                                    "type": "float"
                                },
                                "weight": {
                                    "type": "float"
                                }
                            }
                        },
                        "BallastPoint Vulnerabilities": {
                            "properties": {
                                "name": {
                                    "type": "text",
                                    "fields": {
                                        "keyword": {
                                            "type": "keyword",
                                            "ignore_above": 256
                                        }
                                    }
                                },
                                "value": {
                                    "type": "float"
                                },
                                "weight": {
                                    "type": "float"
                                }
                            }
                        },
                        "Builds": {
                            "properties": {
                                "name": {
                                    "type": "text",
                                    "fields": {
                                        "keyword": {
                                            "type": "keyword",
                                            "ignore_above": 256
                                        }
                                    }
                                },
                                "value": {
                                    "type": "float"
                                },
                                "weight": {
                                    "type": "float"
                                }
                            }
                        },
                        "Checkmarx Vulnerabilities": {
                            "properties": {
                                "name": {
                                    "type": "text",
                                    "fields": {
                                        "keyword": {
                                            "type": "keyword",
                                            "ignore_above": 256
                                        }
                                    }
                                },
                                "value": {
                                    "type": "float"
                                },
                                "weight": {
                                    "type": "float"
                                }
                            }
                        },
                        "Inherent Application Risk": {
                            "properties": {
                                "name": {
                                    "type": "text",
                                    "fields": {
                                        "keyword": {
                                            "type": "keyword",
                                            "ignore_above": 256
                                        }
                                    }
                                },
                                "value": {
                                    "type": "float"
                                },
                                "weight": {
                                    "type": "float"
                                }
                            }
                        },
                        "Nexus Vulnerabilities": {
                            "properties": {
                                "name": {
                                    "type": "text",
                                    "fields": {
                                        "keyword": {
                                            "type": "keyword",
                                            "ignore_above": 256
                                        }
                                    }
                                },
                                "value": {
                                    "type": "float"
                                },
                                "weight": {
                                    "type": "float"
                                }
                            }
                        },
                        "Training credits": {
                            "properties": {
                                "name": {
                                    "type": "text",
                                    "fields": {
                                        "keyword": {
                                            "type": "keyword",
                                            "ignore_above": 256
                                        }
                                    }
                                },
                                "value": {
                                    "type": "float"
                                },
                                "weight": {
                                    "type": "float"
                                }
                            }
                        }
                    }
                },
                "snowAppName": {
                    "type": "text",
                    "fields": {
                        "keyword": {
                            "type": "keyword",
                            "ignore_above": 256
                        }
                    }
                },
                "test": {
                    "type": "text",
                    "fields": {
                        "keyword": {
                            "type": "keyword",
                            "ignore_above": 256
                        }
                    }
                },
                "totalScore": {
                    "type": "float"
                }
            }
        },
        "settings": {
            "index": {
                "creation_date": "1608138304828",
                "number_of_shards": "5",
                "number_of_replicas": "1",
                "uuid": "Awha2RsGQuav3o1mJb1XlQ",
                "version": {
                    "created": "7090199"
                },
                "provided_name": "cam"
            }
        }
    }
}
