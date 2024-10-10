# Challenge 1

Deploy the given architecture diagram for implementing a `Jekyll SSG`. Find the lab [here](https://kodekloud.com/topic/kubernetes-challenge-1/).



1.  <details>
    <summary>kube-config</summary>

    ```bash
    kubectl config set-credentials martin --client-certificate ./martin.crt --client-key ./martin.key
    kubectl config set-context developer --cluster kubernetes --user martin
    ```

    </details>

1.  <details>
    <summary>martin</summary>

    ```bash
    kubectl config use-context developer
    ```

    </details>



    


