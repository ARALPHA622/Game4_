# Game4_
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class BoxContorl : MonoBehaviour
{

    // Update is called once per frame
    void Update()
    {
        transform.Rotate (new Vector3(100, 0, 0)*Time.deltaTime);
    }
}
